# Ex.08 Design of Interactive Image Gallery
## Date:15-10-2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
gall.htmml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Image Gallery</title>
    <link rel="stylesheet" href="style.css">
     <script src="script.js"></script>
</head>
<body bgcolor="cyan">
    <h1 align="center">Image Gallery</h1>
    <div class="gallery">
        <img src="Ajith.png" alt="Ajith" onclick="f1()"  height="200" width="200" id="t1">
        <img src="Arjun.png" alt="Arjun" onclick="f2()" height="200" width="200" id="t2">
        <img src="Asif.png" alt="Asif" onclick="f3()" height="200" width="200" id="t3">
        <img src="Harris.png" alt="Harris" onclick="f4()" height="200" width="200" id="t4">
        <img src="Sakthi.png" alt="Sakthi" onclick="f5()" height="200" width="200" id="t5">
    </div>
    <footer>
        <h2 align="center" >&copy; DESIGNED BY: Srimathi.S</h2>
    </footer>
   
</body>
</html>
style.css
body{
    background-color:aqua;
    height: 100%;
    margin: 0;
    font-size: 20px;
    text-align: center;
}
.container{
    display: flex;
    gap: 15px;
    margin-top: 250px;
    justify-content: center;
}
img{
    border-radius: 20px;
    padding: 10px;
}
script.js
function f1()
{
    document.getElementById("t1").style.transform="scale(2)";
}
function f2()
{
    document.getElementById("t2").style.transform="scale(2)";
}
function f3()
{
    document.getElementById("t3").style.transform="scale(2)";
}
function f4()
{
    document.getElementById("t4").style.transform="scale(2)";
}
function f5()
{
    document.getElementById("t5").style.transform="scale(2)";
}


```
## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-10-15 195823" src="https://github.com/user-attachments/assets/5796f239-4313-4c2f-9a2a-8b8291d5c639" />
<img width="1920" height="1080" alt="Screenshot 2025-10-15 195803" src="https://github.com/user-attachments/assets/a5ea7e18-deab-46f7-98e1-38c041799447" />


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
