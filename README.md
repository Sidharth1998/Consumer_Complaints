# Consume-Complaints
In this project I have analyzed consumer complaints on which products and companies are the customers unhappy with and also products which are doing good.

## Steps Taken
### 1. To merge data
```
data1 = pd.read_csv("ConsumerComplaints-1.csv")
data2 = pd.read_csv("ConsumerComplaints-2.csv")

data = data1.append(data2,ignore_index=True)

# To convert csv file into database
engine = create_engine('sqlite://', echo = True)
data.to_sql("complaints.db",con = engine)
```
