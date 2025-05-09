# Ex.06 Book Front Cover Page Design
# Date:29.04.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover</title>
    <head>
        <style>
            body{
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                width:auto;
            }
            .img img{
                width: 550px;
                height: 800px;
                border: 2px;
            }
            .heading{
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-size: large;
                color: white;
                display: inline;
                position: absolute;
                top: 80px;
                left: 510px;
            }
            .tit{
                position: absolute;
                top: 120px;
                left: 510;
                font-family: Arial, Helvetica, sans-serif;
                font-size: xx-large;
                color: white;
            }
            p{
                font-size: x-large;
            }
            .edi{
                position: absolute;
                bottom: 150px;
                left: 510px;
                font-family: sans-serif;
                font-size: xx-large;
                color: rgb(16, 219, 212);
            }
            .edi hr{
                border: none;
                border-top: 2px solid rgb(16, 219, 212);
                width: 217%;
                margin: 10px 0;
            }
            .name{
                position: absolute;
                bottom: 70px;
                left: 510px;
                font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                font-size: xx-large;
                color: white;
            }
            .my img{
                width: 180px;
                height: 250px;
                position: absolute;
                bottom: 25px;
                left: 830px;
            }
        </style>
    </head>
    <body>
        <div class="cover">
            <div class="img">
                <img src="image.png" alt="mine.png">
            </div>
            <div class="tit">
                <h1>YOUR 
                <br>SECURITY</h1>
                <p>Data encryption & secure backups 
                    <br>
                    to keep your information safe
                </p>
            </div>
            <div class="edi">
                <B>FIRST EDITION</B>
                <hr>
            </div>
            <div class="name">
                <b>THAMIZHARASI G
            </div>
            <div class="my">
                <img src="my.png" alt="">
            </div>
        </div>
    </body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2025-04-29 223902.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
