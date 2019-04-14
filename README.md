# Consumer_Complaints

<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<title>ERP_LAB1 SidharthDugar 1600145C202 CSC</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
[dir="rtl"] #ipython_notebook {
  float: right !important;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
[dir="rtl"] #tabs li {
  float: right;
}
ul#tabs {
  margin-bottom: 4px;
}
[dir="rtl"] ul#tabs {
  margin-right: 0px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons {
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-right {
  padding-top: 1px;
  float: left !important;
}
[dir="rtl"] .list_toolbar .pull-left {
  float: right !important;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
[dir="rtl"] #tree-selector a {
  float: right;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
[dir="rtl"] #new-menu {
  text-align: right;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
[dir="rtl"] #running .col-sm-8 {
  float: right !important;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Importing libraries</span>

<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">from</span> <span class="nn">IPython.display</span> <span class="k">import</span> <span class="n">display</span>
<span class="kn">import</span> <span class="nn">sqlite3</span>
<span class="kn">from</span> <span class="nn">sqlalchemy</span> <span class="k">import</span> <span class="n">create_engine</span>
<span class="kn">import</span> <span class="nn">string</span>
<span class="kn">from</span> <span class="nn">statsmodels.stats.multicomp</span> <span class="k">import</span> <span class="n">pairwise_tukeyhsd</span>
<span class="kn">from</span> <span class="nn">scipy</span> <span class="k">import</span> <span class="n">stats</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[2]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Reading the database file</span>

<span class="n">db_conn</span> <span class="o">=</span> <span class="n">create_engine</span><span class="p">(</span><span class="s1">&#39;sqlite:///complaints.db&#39;</span><span class="p">)</span>
<span class="n">chunks</span> <span class="o">=</span> <span class="mi">25000</span>
<span class="k">for</span> <span class="n">data</span> <span class="ow">in</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s1">&#39;complaints.csv&#39;</span><span class="p">,</span> <span class="n">chunksize</span><span class="o">=</span><span class="n">chunks</span><span class="p">,</span>
                       <span class="n">iterator</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">encoding</span><span class="o">=</span><span class="s1">&#39;utf-8&#39;</span><span class="p">):</span>
    
    <span class="n">data</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="n">col</span><span class="p">:</span> <span class="n">col</span><span class="o">.</span><span class="n">replace</span><span class="p">(</span><span class="s1">&#39;-&#39;</span><span class="p">,</span> <span class="s1">&#39; &#39;</span><span class="p">)</span> <span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">data</span><span class="o">.</span><span class="n">columns</span><span class="p">})</span>
    <span class="n">data</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="n">col</span><span class="p">:</span> <span class="n">col</span><span class="o">.</span><span class="n">strip</span><span class="p">()</span> <span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">data</span><span class="o">.</span><span class="n">columns</span><span class="p">})</span>
    <span class="n">data</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="n">col</span><span class="p">:</span> <span class="n">string</span><span class="o">.</span><span class="n">capwords</span><span class="p">(</span><span class="n">col</span><span class="p">)</span> <span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">data</span><span class="o">.</span><span class="n">columns</span><span class="p">})</span>
    <span class="n">data</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">rename</span><span class="p">(</span><span class="n">columns</span><span class="o">=</span><span class="p">{</span><span class="n">col</span><span class="p">:</span> <span class="n">col</span><span class="o">.</span><span class="n">replace</span><span class="p">(</span><span class="s1">&#39; &#39;</span><span class="p">,</span> <span class="s1">&#39;&#39;</span><span class="p">)</span> <span class="k">for</span> <span class="n">col</span> <span class="ow">in</span> <span class="n">data</span><span class="o">.</span><span class="n">columns</span><span class="p">})</span>
    
    <span class="n">data</span><span class="o">.</span><span class="n">to_sql</span><span class="p">(</span><span class="s1">&#39;data&#39;</span><span class="p">,</span> <span class="n">db_conn</span><span class="p">,</span> <span class="n">if_exists</span><span class="o">=</span><span class="s1">&#39;append&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[3]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Question-1</span>
<span class="c1">#  Which product has the most reported issues respectively in 2013, 2014 and 2015?</span>
<span class="n">query1</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;SELECT ProductName, Company, COUNT(*) as `Complaints`&#39;</span>
                         <span class="s1">&#39;FROM data &#39;</span>
                         <span class="s1">&#39;GROUP BY ProductName &#39;</span>
                         <span class="s1">&#39;ORDER BY `Complaints` DESC&#39;</span><span class="p">,</span> <span class="n">db_conn</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">y</span><span class="o">=</span><span class="n">query1</span><span class="o">.</span><span class="n">ProductName</span><span class="p">[</span><span class="mi">0</span><span class="p">:</span><span class="mi">9</span><span class="p">],</span> <span class="n">x</span><span class="o">=</span><span class="n">query1</span><span class="o">.</span><span class="n">Complaints</span><span class="p">[</span><span class="mi">0</span><span class="p">:</span><span class="mi">9</span><span class="p">])</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[3]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x116d86940&gt;</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Question-2</span>
<span class="c1"># Which company is doing best in terms of debt collection, i.e. having least number of this issue?</span>
<span class="n">query2</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;SELECT Company, COUNT(*) as `Complaints` &#39;</span>
                           <span class="s1">&#39;FROM data &#39;</span>
                           <span class="s1">&#39;WHERE ProductName = &quot;Debt collection&quot; &#39;</span>
                           <span class="s1">&#39;GROUP BY Company &#39;</span>
                           <span class="s1">&#39;ORDER BY `Complaints` DESC &#39;</span>
                           <span class="s1">&#39;LIMIT 10 &#39;</span><span class="p">,</span> <span class="n">db_conn</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">y</span><span class="o">=</span><span class="n">query2</span><span class="o">.</span><span class="n">Company</span><span class="p">,</span> <span class="n">x</span><span class="o">=</span><span class="n">query2</span><span class="o">.</span><span class="n">Complaints</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[4]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x1183693c8&gt;</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[8]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Question-3</span>
<span class="c1"># Show the trends for issue for mortgage product from July 2013 till July 2014.</span>
<span class="n">query3</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;Select DateReceived, COUNT(*) AS `Day` &#39;</span>
                           <span class="s1">&#39;FROM data &#39;</span>
                           <span class="s1">&#39;WHERE ProductName= &quot;Mortgage&quot; &#39;</span>
                           <span class="s1">&#39;AND  DateReceived BETWEEN &quot;2013-07-08&quot; AND &quot;2014-07-31&quot; &#39;</span>
                           <span class="s1">&#39;GROUP BY DateReceived &#39;</span><span class="p">,</span> <span class="n">db_conn</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">lineplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="n">query3</span><span class="o">.</span><span class="n">DateReceived</span><span class="p">[:</span><span class="mi">5</span><span class="p">],</span> <span class="n">y</span><span class="o">=</span><span class="n">query3</span><span class="o">.</span><span class="n">Day</span><span class="p">[:</span><span class="mi">5</span><span class="p">])</span>

<span class="c1"># Could not show all the dates at one go</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[8]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x11763ac50&gt;</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Question-4</span>
<span class="c1"># Show the distribution of issues reporting for states using pie chart.</span>
<span class="n">query4</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;SELECT StateName, COUNT(*) AS `Issue` &#39;</span>
                           <span class="s1">&#39;FROM data &#39;</span>
                           <span class="s1">&#39;GROUP BY StateName &#39;</span>
                           <span class="s1">&#39;ORDER BY `Issue` DESC &#39;</span>
                           <span class="s1">&#39;LIMIT 4 &#39;</span><span class="p">,</span> <span class="n">db_conn</span><span class="p">)</span>
<span class="n">labels</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;CA&#39;</span><span class="p">,</span> <span class="s1">&#39;FL&#39;</span><span class="p">,</span> <span class="s1">&#39;TX&#39;</span><span class="p">,</span> <span class="s1">&#39;NY&#39;</span><span class="p">]</span>
<span class="n">sizes</span> <span class="o">=</span> <span class="p">[</span><span class="mi">9198</span><span class="p">,</span><span class="mi">6271</span><span class="p">,</span><span class="mi">5463</span><span class="p">,</span><span class="mi">4389</span><span class="p">]</span>
<span class="n">colors</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;gold&#39;</span><span class="p">,</span> <span class="s1">&#39;yellowgreen&#39;</span><span class="p">,</span> <span class="s1">&#39;lightcoral&#39;</span><span class="p">,</span> <span class="s1">&#39;lightskyblue&#39;</span><span class="p">]</span>
<span class="n">explode</span> <span class="o">=</span> <span class="p">(</span><span class="mf">0.1</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">,</span> <span class="mi">0</span><span class="p">)</span>  <span class="c1"># explode 1st slice</span>
 
<span class="c1"># Plot</span>
<span class="n">plt</span><span class="o">.</span><span class="n">pie</span><span class="p">(</span><span class="n">sizes</span><span class="p">,</span> <span class="n">explode</span><span class="o">=</span><span class="n">explode</span><span class="p">,</span> <span class="n">labels</span><span class="o">=</span><span class="n">labels</span><span class="p">,</span> <span class="n">colors</span><span class="o">=</span><span class="n">colors</span><span class="p">,</span>
<span class="n">autopct</span><span class="o">=</span><span class="s1">&#39;</span><span class="si">%1.1f%%</span><span class="s1">&#39;</span><span class="p">,</span> <span class="n">shadow</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">startangle</span><span class="o">=</span><span class="mi">140</span><span class="p">)</span>

<span class="c1"># Was not able to show all states</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[10]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>([&lt;matplotlib.patches.Wedge at 0x1172889b0&gt;,
  &lt;matplotlib.patches.Wedge at 0x11727f438&gt;,
  &lt;matplotlib.patches.Wedge at 0x11727feb8&gt;,
  &lt;matplotlib.patches.Wedge at 0x117275978&gt;],
 [Text(-1.08413,-0.514458,&#39;CA&#39;),
  Text(0.782566,-0.773039,&#39;FL&#39;),
  Text(0.857697,0.688735,&#39;TX&#39;),
  Text(-0.354489,1.04132,&#39;NY&#39;)],
 [Text(-0.632408,-0.300101,&#39;36.3%&#39;),
  Text(0.426854,-0.421658,&#39;24.8%&#39;),
  Text(0.467835,0.375674,&#39;21.6%&#39;),
  Text(-0.193358,0.56799,&#39;17.3%&#39;)])</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[11]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Question-5</span>
<span class="c1"># Which mode of report issuing became popular from 2013 to 2015 and </span>
<span class="c1"># which one got declined (assume one quarter as the reference time-period).</span>
<span class="n">query5</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;SELECT DateReceived, SubmittedVia AS `Mode`, COUNT(*) AS `Count` &#39;</span>
                           <span class="s1">&#39;FROM data &#39;</span>
                           <span class="s1">&#39;GROUP BY SubmittedVia &#39;</span>
                           <span class="s1">&#39;ORDER BY `Count` DESC &#39;</span>
                           <span class="s1">&#39;LIMIT 10 &#39;</span><span class="p">,</span><span class="n">db_conn</span><span class="p">)</span>
<span class="n">sns</span><span class="o">.</span><span class="n">barplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="n">query5</span><span class="o">.</span><span class="n">Mode</span><span class="p">,</span> <span class="n">y</span><span class="o">=</span><span class="n">query5</span><span class="o">.</span><span class="n">Count</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

<div class="prompt output_prompt">Out[11]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x11726ab38&gt;</pre>
</div>

</div>

<div class="output_area">

<div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
