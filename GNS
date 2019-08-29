<html>
<head>
<title> G and S </title>
<script>
var font = 0, loading;
function start() {
loading = window.setInterval("incr()",100);
}
 function incr() {
 font = font +1;
 display.innerHTML="TEXT-GROWING:" + font + "pt";
 display.style.fontSize=font + "pt";
 if (font > 50) {
 window.clearTimeout(loading);
 loading =window.setInterval("decr()",100);
 }
 display.style.color="red";
 }
 
 function decr() {
 font = font-1;
 display.innerHTML="TEXT SHRINKING:" + font + "pt";
 display.style.fontSize=font + "pt";
 if (font==5) {
 window.clearTimeout(loading);
 loading =window.setInterval("incr()",100);
 }
 display.style.color="blue";
 }
 </script>
 </head>
 <body style="background: #FA8072;" onload="start()">

<p style="margin-top:0px;position:absolute;top:20px;right:20px;" id="display"></p>

</body>
</html>
 
