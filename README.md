# Consumer-Complaints
In this project I have analyzed consumer complaints on which products and companies are the customers unhappy with and also products which are doing good.

### To merge data and converting csv file to db(database) file and read from db file
```
data1 = pd.read_csv("ConsumerComplaints-1.csv")
data2 = pd.read_csv("ConsumerComplaints-2.csv")

data = data1.append(data2,ignore_index=True)

# convert the data into csv file
data.to_csv("complaints.csv",index=False)

# Convert csv to db file
db_conn = create_engine('sqlite:///complaints.db')
chunks = 25000
for data in pd.read_csv('complaints.csv', chunksize=chunks,
                       iterator=True, encoding='utf-8'):
    
    data = data.rename(columns={col: col.replace('-', ' ') for col in data.columns})
    data = data.rename(columns={col: col.strip() for col in data.columns})
    data = data.rename(columns={col: string.capwords(col) for col in data.columns})
    data = data.rename(columns={col: col.replace(' ', '') for col in data.columns})
    
    data.to_sql('data', db_conn, if_exists='append')
```

### Now you can query from database and convert it into pandas dataFrame
#### Example
```
# Question-1
#  Which product has the most reported issues respectively in 2013, 2014 and 2015?
query1 = pd.read_sql_query('SELECT ProductName, Company, COUNT(*) as `Complaints`'
                         'FROM data '
                         'GROUP BY ProductName '
                         'ORDER BY `Complaints` DESC', db_conn)
sns.barplot(y=query1.ProductName[0:9], x=query1.Complaints[0:9])
```
<img src="https://github.com/Sidharth1998/Consumer_Complaints/blob/master/plot1.png" width="500" height="300">

### Complete project can be seen in the Ipython notebook uploaded above.
