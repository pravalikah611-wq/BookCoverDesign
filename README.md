# Ex.06 Book Front Cover Page Design
## Date: 12.10.2025
## AIM:
To design a book front cover page using HTML and CSS.
## DESIGN STEPS:
### Step 1:
Create a Django Admin project.
### Step 2:
Create an app in the Django interface.
### Step 3:
Create a folder named 'static' in the app folder.
### Step 4:
Create a new HTML file in the static folder.
### Step 5:
Write the HTML code with relevant CSS properties.
### Step 6:
Choose the appropriate style and color scheme.
### Step 7:
Insert the images in their appropriate places.
### Step 8:
Publish the website in the LocalHost.
## PROGRAM:
```<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Book Cover Page</title>
<style>
div{
display: inline-block;
margin: auto;
margin-top: 3%;
margin-left: 33%;
text-align: center;
border: 5px solid rgb(174, 229, 11);
width: 35%;
}
body{
background-image: url('book.jpg');
background-size: cover;
background-repeat: no-repeat;
color: white;
}
span{
font-size: 22px;
}
</style>
</head>
<body>
<div>
<p style="border-bottom: 3px solid white; font-size: 25px;">SEC Insights</p>
<h1>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>
<P style="font-size: 20px;">Deep Dive in HTML, CSS & JS Basics Top Seller of
2025</P>
<img src="image.png" alt="Book Cover Image" width="250" height="200">
<h2>SPECIAL EDITION</h2>
<tfoot>
<tr>
<td><span>Type Your Name</span></td>
<td><span>SEC</span></td>
</tr>
</tfoot>
</div>
</body>
</html>
```
## OUTPUT:
![alt text](image-1.png)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed
successfully.