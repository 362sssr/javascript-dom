#JAVASCRIPT-DOM 
 HTML 
<html> 
<head> 
<title> 
dom 
</title> 
<link rel="stylesheet" href="domcss.css"> 
</head> 
<body> 
<body background="E:\AMMU\naane\js.jpg"> 
<h4>ENTER MY NAME:<br><input type="text" onchange="chicken()"  id="p1"></h4> 
<button onclick="mutton()"><b>click me</b></button> <p id="p2"></p> 
<script src="domjs.js"> 
</script> 
</body> 
</html>


 #CSS 
body{background-size:contain;} 
button{position:absolute;bottom:100px;right:280px;width:150px;hei ght:50px;font-size:20px;background-color:yellow;text transform:uppercase;} 
P{position:absolute;bottom:50px;right:200px;font-size:20px;} 
h4{position:absolute;top:220px;right:280px;font 
size:20px;background-color:yellow;} 
input{width:200px;background 
color:black;color:white;position:absolute;top:30px;right:-10px;text align:center;} 
 
 
 #JAVASCRIPT 
function mutton()  
{ 
document.getElementById("p2").innerHTML ="I'M THE QUEEN OF  MY WORLD"; 
document.getElementById("p2").style.color ="mediumturquoise"; } 
function chicken() 
{ 
let x=document.getElementById("p1"); 
x.value=x.value.toUpperCase(); 
}
