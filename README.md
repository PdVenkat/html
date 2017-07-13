<!DOCTYPE html>
<html>
<head>
<style>
h4
{
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/
4.7.0/css/font-awesome.min.css">
}
h1
{
background-color:silver;
margin-top:100px;
margin-bottom:100px;
margin-right:150px;
margin-left:80px;
padding-top:100px;
padding-bottom:10px;
padding-right:50px;
padding-left:80px;
border-right:solid;
border-left:solid;
border-top:dotted;
border-bottom:dotted;
height:200px;
width:50%;
background-color:powderblue;
text-align:center;
}
h2
{
border:1px solid black;
margin-left:300px;
outline-color:cyan;
outline-style:double;
outline-width:thinner;
text-align:center;
width:150px;
text-decoration:underline;
text-transform:uppercase;
text-shadow:3px 2px solid black;
}
h3
{
font-variant:small-caps;
}
p
{
width:300px;
border: 25px solid pink;
padding:25px;
margin:200px;
text-align:justify;
letter-spacing:1px;
line-height:1.8;
word-spacing:1px;
font-family:"Times New Roman",Times,serif;
font-style:italic;
font-size:100%;
font-weight:bold;
}
a:link{
color:white;
padding:14px 25px;
text-align:center;
background-color:red;
text-decoration:none;
display:inline-block;
}
a:visited{
color:blue;
padding:14px 25px;
text-align:center;
background-color:transparent;
text-decoration:none;
display:inline-block;
}
a:hover{
color:white;
padding:14px 25px;
text-align:center;
background-color:blue;
text-decoration:none;
display:inline-block;
}
a:active{
color:white;
padding:14px 25px;
text-align:center;
background-color:powderblue;
text-decoration:none;
display:inline-block;
}
ul
{
list-style-type:square inside;
background-color:#ff9999;
width:300px;
padding: 20px;
}
ol
{
background:#3399ff;
padding: 20px;
width:300px;
}
ul li
{
background: #ffe5e5;
padding: 5px;
margin-left:35px;
}
ol li
{
background:#cce5ff;
margin-left:35px;
padding:5px;
}
table{
border-collapse:
collapse;
}
table,th,td
{
border:1px solid black;
height:20px;
width:50%;
text-align:left;
padding:15px;
}
tr:hover
{
background-color:powderblue
}
tr:nth-child(even)
{
background-color:#f2f2f2
}
th
{
background-color:#4caf50;
color:white;
}
h5.hidden
{
display:none;
}
div.ex1
{
width:500px;
margin:auto;
border:3px solid #73ad21;
}
div.ex2
{
max-width:500px;
margin:auto;
border:3px solid #73ad21;
}
img
{
position: absolute;
left: 0px;
top: 0px;
z-index: -1;
}
</style>
</head>
<body>
<h1>
hello
</h1>
<h2>
Welcome
</h2>
<h3>
Font Variant.
</h3>
<p><b> This text is actually to check whether this box model is working properly or not.</b></p>
<h4><i class="fa fa-cloud"></i>
</h4>
<a href="default.asp" target="_blank">This is a link</a>
<ul>
<li>tea</li>
<li>coffee</li>
<li>juice</li>
</ul>
<ol>
<li>tea</li>
<li>coffee</li>
<li>juice</li>
</ol>
<div style="overflow-x:auto;">
<table>
<tr>
<th>Firstname</th>
<th>lastname</th>
</tr>
<tr>
<td>priya</td>
<td>dharshini</td>
</tr>
<tr>
<td>prathi</td>
<td>pandi</td>
</tr>
</table>
</div>
<h5 class="hidden">
hdufiweuqorjfkdjvh
</h5>
<div class="ex1">This div element has width:500px;
</div>
<div class="ex2">This div element has max width:500px;
</div>
<img src="Hydrangeas.jpg" width="100" height="140">
<p>Because the image has a z-index of -1 , it will be places behind the text.</p>
</body>
</html>
