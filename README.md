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
hari.html

<html>
    <head>
<style>
.container
{
    position: relative;
display: block;
margin-left: 35%;
margin-right: 50%;
    width: 300px;
    height: 300px;
}
.background-image
{
   
  
    width: 260%;
    height: 390%;
  
}
.user
{
    position: absolute;
    bottom: -690px;
    right: -440px;
    width: 190px;
    height: auto;
}
.topic
{
    position: absolute;
   top: 150px;
   left: 50px;
   color: azure;
   font-style: italic;
    font-size: 60px;
}
.sub-topic
{
    position: absolute;
   top: 420px;
   left: 50px;
   color: azure;
   font-style: italic;
    font-size: 25px;
}
.line-below
{
    position: absolute;
    top: 1030px;
    left: 50px;
    color: aliceblue;
    font-style: normal;
    font-size: 39px;
}
.line-above
{
    position: absolute;
    top: 950px;
    left: 50px;
    color: aliceblue;
    font-style: normal;
    font-size: 30px;
}
.line--below
{
    position: absolute;
    top: 1040px;
    left: 610px;
    color: aliceblue;
    font-style: normal;
    font-size: 30px;
    font-style: bold;
}
.topon
{
    position: absolute;
   top: 20px;
   left: 50px;
   color: azure;
   font-style: italic;
    font-size: 30px;
}


</style>
    </head>
    <body>
        <div class="container">
            <img src="hari.jpg" alt="" class="background-image">
            <img src="hari1.jpg" alt="" class="user">
            <h1 class="topic">DESIGN OF WEB AND CSS</h1>
            <h2 class="sub-topic">(With HTML and CSS)</h2>
            <p class="line-above">TWENTY FIFTH EDITION</p>
            <p class="line-below"><b>HARIRAM R</b></p>
            <p class="line--below">SEC</p>
            <p class="topon">EXPERT INSIGHT</p>
        </div>
    </body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-02 204207.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
