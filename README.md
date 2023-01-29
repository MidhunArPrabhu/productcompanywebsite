# Product Company Website
## AIM:
To develop a static company website to display the sale of products.

## Design Steps:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## Code:

home.html

```
<!DOCTYPE html>
<html lang="en">
<head>
<title>
Home Page
</title>
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="/static/css/styles.css">
<style>
.text{
color:blueviolet;
font-family:'Lucida Sans';
font-size: 30px;
text-align:center;
}
img{
height: 150px;
width: 150px;
align-items:center;
}
</style>
</head>
<body>
<div class="home">
<div class="header">
<header>
<div class=logo></div>
<div class=h>
<a href="home.html" title="Home" style="color: darkred; text-decoration:
none;"><b>Home</b></a></div>
<div class="prod">
<a href="products.html" title="Products" style="color: darkred; text-decoration:
none;"><b>Products</b></a>
</div>
<div class="people">
<a href="people.html" title="People" style="color:darkred; text-decoration:
none;"><b>People</b></a>
</div>
<div class="contact">
<a href="contact.html" title="Contact Us" style="color:darkred;
text-decoration: none;"><b>Contact Us</b></a>
</div>
</header>
<div class="title">
<h1>Fashion style</h1>
</div><br>
<div class="content">
<div class="text">
<marquee><b>Feel BEAUTY through our Store</b></marquee>
<p style="color:purple; font-family:'Tahoma'; font-size:20px;"> This is the Official
Website of our Fancy Store</p>
</div>
<p>Buy Fancy items and Cosmetics online for Women from <span
style="background-color:lime">Fashion style</span>
for Rs.100 | Buy cosmetics in ONE SIZE online | 7 Days Returns | Trend
setting models | And much more</p>
<br>
<center>
<img src="/static/images/ben1.png">
<img src="/static/images/ben2.jpg">
<img src="/static/images/ben3.png">
<img src="/static/images/ben4.jpg">
<img src="/static/images/ben5.png">
<img src="/static/images/ben6.png">
<img src="/static/images/ben7.png">
</center>
</div>
<div class="footer">
<footer style="color:white">
Copyright &copy;2023 Developed by Langford</footer></div>
</div>
</div>
</body>
</html>


products.html


<!DOCTYPE html>
<html lang="en">
<head>
<title>
Products
</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="/static/css/styles.css">
<style>
.home{
height: 1555px;
width: 85%;
border: 12px solid red;
padding-left:10px;
padding-right:10px;
margin-left: auto;
margin-right:auto;
background-color:cyan;
}
.text{
color:blueviolet;
font-family:'Lucida Sans';
font-size: 30px;
text-align:center;
}
.content{
border:3px solid red;
background-color: white;
width:98%;
height:1190px;
padding:10px;
margin-left:auto;
margin-right:auto;
}
.ph1{
background-image: url(/static/images/item1.png);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:200px;
width:30%;
position:relative;
left: 50px;
}
.l1{
color: gold;
position:relative;
right:380px;
}
.ph2{
background-image: url(/static/images/item2.png);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:200px;
width:30%;
position:relative;
left: 50px;
}
.l2{
color: sandybrown;
position:relative;
right:380px;
}
.ph3{
background-image: url(/static/images/item3.png);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:210px;
width:30%;
position:relative;
left: 50px;
}
.l3{
color: burlywood;
position:relative;
right:380px;
}
.ph4{
background-image: url(/static/images/item4.png);
background-position-x: center;
border:1px solid black;
height:200px;
width:30%;
position:relative;
left: 700px;
bottom:930px;
background-size: 310px;
background-repeat: no-repeat;
}
.l4{
color: burlywood;
position:relative;
left:270px;
bottom: 930px;
}
.ph5{
background-image: url(/static/images/item5.png);
background-position-x: center;
border:1px solid black;
height:200px;
width:30%;
position:relative;
left: 700px;
bottom:930px;
background-size: 280px;
background-repeat: no-repeat;
}
.l5{
color: cadetblue;
position:relative;
left:270px;
bottom: 930px;
}
.ph6{
background-image: url(/static/images/item6.png);
background-position-x: center;
border:1px solid black;
height:200px;
width:30%;
position:relative;
left: 700px;
bottom:930px;
background-size: 280px;
background-repeat: no-repeat;
}
.l6{
color: crimson ;
position:relative;
left:270px;
bottom: 930px;
}
.bot{
text-align:center;
font-size:larger;
color:magenta;
}
</style>
</head>
<body>
<div class="home">
<div class="header">
<header>
<div class=logo></div>
<div class=h>
<a href="home.html" title="Home" style="color: darkred; text-decoration:
none;"><b>Home</a></div>
<div class="prod">
<a href="products.html" title="Products" style="color: darkred; text-decoration:
none;"><b>Products</b></a>
</div>
<div class="people">
<a href="people.html" title="People" style="color:darkred; text-decoration:
none;"><b>People</b></a>
</div>
<div class="contact">
<a href="contact.html" title="Contact Us" style="color:darkred;
text-decoration: none;"><b>Contact Us</b></a>
</div>
</header>
<div class="title">
<h1>Products</h1>
</div><br>
<div class="content">
<div class="text">
<p>These are the products that are available now</p>
</div>
<div class="ph1"></div>
<div class="l1"><p align="center"><b>Lipstick<br> Price:
1999.00</b><br><br><br><br></p></div>
<div class="ph2"></div>
<div class="l2"><p align="center"><b>Eyeliner<br> Price:
1899.00</b><br><br><br><br></p></div>
<div class="ph3"></div>
<div class="l3"><p align="center"><b>Compact Powder<br> Price:
1999.00</b><br<br><br><br></p></div>
<div class="ph4"></div>
<div class="l4"><p align="center"><b>Foundation<br> Price:
6999.00</b><br><br><br><br></p></div>
<div class="ph5"></div>
<div class="l5"><p align="center"><b>Make-up Brush<br> Price:
3999.00</b><br><br><br><br></p></div>
<div class="ph6"></div>
<div class="l6"><p align="center"><b>Primer<br> Price:
5999.00</b><br><br><br><br></p></div>
</div>
<div class="bot"><p>To Order Online: Call 90 80 70 2009</p></div>
<div class="footer">
<footer style="color:white">
Copyright &copy;2023 Developed by Lanford</footer></div>
</div>
</div>
</body>
</html>


people.html


<!DOCTYPE html>
<html lang="en">
<head>
<title>
People
</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="/static/css/styles.css">
<style>
.home{
height: 3000px;
width: 85%;
border: 12px solid red;
padding-left:10px;
padding-right:10px;
margin-left: auto;
margin-right:auto;
background-color:cyan;
}
.text{
color:blueviolet;
font-family:'Lucida Sans';
font-size: 30px;
text-align:center;
}
.content{
border:2px solid green;
background-color:lime;
width:98%;
height:2690px;
padding:10px;
margin-left:auto;
margin-right:auto;
}
.ceoph{
background-image: url(/static/images/P1.jpg);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:3px solid gold;
height:300px;
width:20%;
position:relative;
left: 0px;
margin-left:auto;
margin-right: auto;
}
.ceo{
color: red;
position:relative;
text-align:center;
}
.manph1{
background-image: url(/static/images/P2.jpg);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:300px;
width:20%;
position:relative;
margin-left:auto;
margin-right:auto;
}
.man1{
color: red;
position:relative;
text-align:center;
}
.manph2{
background-image: url(/static/images/P3.jpg);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:300px;
width:20%;
position:relative;
margin-left:auto;
margin-right:auto;
}
.man2{
color: red;
position:relative;
text-align:center;
}
.amph1{
background-image: url(/static/images/P4.jpg);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:300px;
width:20%;
position:relative;
margin-left:auto;
margin-right:auto;
}
.am1{
color: red;
position:relative;
text-align:center;
}
.amph2{
background-image: url(/static/images/P6.jpg);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:220px;
width:20%;
position:relative;
margin-left:auto;
margin-right:auto;
}
.am2{
color: red;
position:relative;
text-align:center;
}
.amph3{
background-image: url(/static/images/P5.jpg);
background-size: 250px;
background-position-x: center;
background-repeat: no-repeat;
border:1px solid black;
height:250px;
width:20%;
position:relative;
margin-left:auto;
margin-right:auto;
}
.am3{
color: red;
position:relative;
text-align:center;
}
</style>
</head>
<body>
<div class="home">
<div class="header">
<header>
<div class=logo></div>
<div class=h>
<a href="home.html" title="Home" style="color: darkred; text-decoration:
none;"><b>Home</b></a></div>
<div class="prod">
<a href="products.html" title="Products" style="color: darkred; text-decoration:
none;"><b>Products</b></a>
</div>
<div class="people">
<a href="people.html" title="People" style="color:darkred; text-decoration:
none;"><b>People</b></a>
</div>
<div class="contact">
<a href="contact.html" title="Contact Us" style="color:darkred;
text-decoration: none;"><b>Contact Us</b></a>
</div>
</header>
<div class="title">
<h1>People</h1>
</div><br>
<div class="content">
<div class="text">
<p>Board Members</p>
<h4><u>Chairman</u></h4>
</div>
<div class="ceoph"></div>
<div class="ceo"><p align="center"><b><h2>VAISHALI</h2></b></div>
<br>
<div class="text">
<p><b><u>Head executives</u></b></p><br>
</div>
<div class="manph1"></div>
<div class="man1"><p align="center"><b><h2>Jack Carla</h2></b></p></div>
<div class="manph2"></div>
<div class="man2"><p><b><h2>ABI</h2></b></p></div>
<br>
<div class="text"><p><b><u>Managers</u></b></p></div><br>
<div class="amph1"></div>
<div class="am1"><p align="center"><b><h2>RAHUL</h2></b></p></div>
<div class="amph2"></div>
<div class="am2"><p align="center"><b><h2>BHARATH</h2></b></p></div>
<div class="amph3"></div>
<div class="am3"><p
align="center"><b><h2>KAMESH</h2></b></p></div><br>
<div class="text">Thank you so much for your kind support!<br>Hope our
products had made you more B-E-A-UTIFUL!</div>
</div>
<div class="footer">
<footer style="color:white">
Copyright &copy;2023 Developed by Lanford</footer></div>
</div>
</div>
</body>
</html>


contact.html


<!DOCTYPE html>
<html lang="en">
<head>
<title>
Contact Us
</title>
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="/static/css/styles.css">
<style>
.text{
color:blueviolet;
font-family:'Lucida Sans';
font-size: 30px;
text-align:center;
}
</style>
</head>
<body>
<div class="home">
<div class="header">
<header>
<div class=logo></div>
<div class=h>
<a href="home.html" title="Home" style="color: darkred; text-decoration:
none;"><b>Home</b></a></div>
<div class="prod">
<a href="products.html" title="Products" style="color: darkred; text-decoration:
none;"><b>Products</b></a>
</div>
<div class="people">
<a href="people.html" title="People" style="color:darkred; text-decoration:
none;"><b>People</b></a>
</div>
<div class="contact">
<a href="contact.html" title="Contact Us" style="color:darkred;
text-decoration: none;"><b>Contact Us</b></a>
</div>
</header>
<div class="title">
<h1>Contact Us</h1>
</div><br>
<div class="content">
<div class="text">
<p><b>Here are the details about us
<h5>Do contact us for any need</h5></b></p>
</div>
<b><h2>Contact Information:</h2></b>
<p><b>&emsp;&ensp;Address:</b>
Saveetha Nagar,Thandalam
</p>
<ul>
<li><b>Landline:</b> 4871683254</li>
<li><b>Mobile</b>:9786744995</li>
<li><b>Facebook</b>: fb/cartoonpro</li>
<li><b>Email Id:</b>vaishu@fancyuniv.com</li>
</ul>
<div style="text-align: center;color:violet;font-size:20px;"><b>Use our services
and Beautify Yourself!</b></div>
</div>
<div class="footer">
<footer style="color:white">
Copyright &copy;2023 Developed by Jenifer Lanford</footer></div>
</div>
</div>
</body>
</html>


styles.css


.home{
height: 700px;
width: 85%;
border: 12px solid red;
padding-left:10px;
padding-right:10px;
margin-left: auto;
margin-right:auto;
background-color:cyan;
}
.content{
border:1px solid whitesmoke;
background-color: white;
width:95%;
height:1190px;
padding:10px;
margin-left:auto;
margin-right:auto;
}
.header{
height: 128px;
width:100%;
background-image: url(/static/images/header.jpg);
background-size: cover;
}
.logo{
height:18%;
width: 10%;
position:absolute;
background-image: url(/static/images/icon.png);
background-size:cover;
}
.prod{
height:auto;
width:auto;
position:relative;
bottom:10px;
left:550px;
border:4px solid transparent;
text-align:center;
display: inline;
padding:15px;
font-family:'Gill Sans MT';
font-size: large;
}
.prod:hover{
background-color:red;
}
.people{
height:auto;
width:auto;
position:relative;
bottom:10px;
left:700px;
border:4px solid transparent;
text-align:center;
display: inline;
padding:15px;
font-family:'Gill Sans MT';
font-size: large;
}
.people:hover{
background-color:red;
}
.contact{
height:20px;
width:10%;
position:relative;
bottom:45px;
left:1000px;
border:4px solid transparent;
text-align:center;
padding:15px;
font-family:'Gill Sans MT';
font-size: large;
}
.contact:hover{
background-color:red;
}
.h{
height:20px;
width:10%;
position:relative;
top:30px;
left:200px;
border:4px solid transparent;
text-align:center;
padding:15px;
font-family:'Gill Sans MT';
font-size: large;
}
.h:hover{
background-color:red;
overflow:hidden;
}
.footer{
border: 15px solid red;
width:98%;
height:10px;
position:relative;
bottom: 1px;
background-color:red;
text-align:center;
}
.title{
border:2px solid pink;
background-color:yellow;
padding:1px;
width:99.7%;
height: 70px;
text-align:center;
font-family:'Impact';
margin-left:auto;
margin-right: auto;
}
.content{
border:1px solid red;
background-color: white;
width:98%;
height:400px;
padding:10px;
margin-left:auto;
margin-right:auto;
}

```
## Output:
![Screenshot (47)](https://user-images.githubusercontent.com/118787344/215344055-ab4184fb-c523-45ae-9b3a-c298abbf5e76.png)

![WhatsApp Image 2023-01-29 at 10 46 44 PM](https://user-images.githubusercontent.com/118787344/215344061-1de8b243-7ef6-46fe-934b-5aa6b1be1fda.jpeg)

![WhatsApp Image 2023-01-29 at 10 46 51 PM](https://user-images.githubusercontent.com/118787344/215344184-d5f8a24c-4539-4533-9aa4-ccdfa2cd28c0.jpeg)

![WhatsApp Image 2023-01-29 at 10 47 01 PM](https://user-images.githubusercontent.com/118787344/215344361-9d506782-a9e9-4d12-a794-92c3a67a7e2f.jpeg)




## HTML Validator:

![Screenshot (48)](https://user-images.githubusercontent.com/118787344/215344277-76d2f457-2b6f-429a-ab11-77c6f16d2a3d.png)



## Result:
The program for designing company website for sale of products using HTML and CSS is completed successfully.
