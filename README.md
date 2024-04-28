# Ex.06 Book Front Cover Page Design
## Date: 28-04-2024

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
        <title>Book Cover</title>
    <style>
        body{
            margin: 0;
            padding: 0;
            background-color: white;
        }
        .book-cov{
            width: 500px;
            height: 700px;
            background-color:white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.7);
            margin: 50px auto;
            position: relative;
        }
        .book-cov .insight{
            position: absolute;
            top: 19px;
            font-size: 25px;
            left: 2px;
            color: brown;
        }
        .book-cov .title1{
            position:absolute;
            top: 175px;
            font-size: 33px;
            left: 5px;
            font-style: normal;
            font-weight:bold;
            color:blanchedalmond;
        }

        .book-cov .edition{
            position:absolute;
            bottom: 40px;
            left: 6px;
            font-weight: bolder;
            font-size: 22px;
            font-style: normal;
            color:aquamarine;
        }
        .book-cov .author{
            position:absolute;
            bottom: 8px;
            font-size: 26px;
            font-style: italic;
            font-weight:bold;
            left: 4px;
            color: rgb(6, 163, 220);

        }
        .book-cov .image{
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
        }
        .book-cov .mypic{
            position: relative;
            top:500px;
            left: 320px;
            width : 160px;
            height: 185px;
            background-size:fit;
        }
    </style>
    </head>
    <body>
        <div class="book-cov">
            <img src="imgcov.jpg" alt="imgcov" class="image">
            <div class="insight">EXPERT INSIGHT</div>
            <div class="title1">BEGINNERS GUIDE TO STOCK MARKET</div>
            <img src="mypic.jpg" alt="me" class="mypic">
            <div class="edition">Extended Edition</div>
            <div class="author">-Karthikeyan M</div>
        </div>
    </body>
    
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-04-28 214420.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
