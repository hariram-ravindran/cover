# Ex.06 Book Front Cover Page Design
## Date:1.12.2024

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
```
<html>
    <head>
        <style>
            body {
                margin: 10;
                padding: 0;
                background-color: #b6b6b6; 
            }
            .container {
                position: relative; 
                width: 360px; 
                height: 500px; 
                margin: 5px auto; 
                background-image: url(hari.jpg);
                background-size: contain; 
                border: 2px solid rgb(255, 255, 255);
            }
            .title {
                position: absolute;
                letter-spacing: 5;
                top: 10px;
                left: 45;
                color: antiquewhite;
                text-align: left;
                font-family:sans-serif;
                font-weight: 150;
                margin: 0;
            }
            .sub{
                position: absolute;
                letter-spacing: 5;
                top: 54px;
                left: 45;
                color:white;
                text-align: left;
                font-family:sans-serif;
                font-weight: 150;
                margin: 0;
            }
            .edition{
                position: absolute;
                letter-spacing: 3;
                top: 15px;
                right: 4;
                color:aliceblue;
                text-align: right;
                font-size: 8;
                font-style:normal;
                font-weight: 15;
                margin: 0;

            }
            .imag {
                position: absolute; 
                bottom: 10px; 
                right: 15px; 
                width: 80px; 
                border-radius: 5%;
                border: 2px solid rgb(223, 229, 230); 
            }
            .author {
                position: absolute;
                bottom: 8px;
                left: 22px; /* Adjust to avoid overlapping with the image */
                font-size: 13px;
                font-family: Arial, Helvetica, sans-serif;
                color: rgb(228, 241, 241);
                letter-spacing: 3;
                margin: 0;
            }
        </style>
        <title>My Book</title>
    </head>
    <body>
        <div class="container">
            <h1 class="title">HR/RH</h1>
            <h2 class="sub">APPLICATION <br>FOR <br><b>W</b><br><b>E</b><br><b>B</b><br><b></b>AND</b><br><b>CSS</b><br></h2></h2>
            <img src="hari1.jpg" class="imag">
            <h4 class="author">R HARI RAM</h4>
            <h6 class="edition">25 EDITION</h6>
        </div>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-01 195700.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
