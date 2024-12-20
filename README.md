# Ex.06 Book Front Cover Page Design
## Date:05.12.2024

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
cover.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COVER</title>
    <!-- <link ref="stylesheet" href="bg imag.png"> -->
    <style>
        * {
            padding: 0px;
            margin: 0px;
        }

        #image {
            margin-top: 20px;
            height: 95%;
            width: 50% ;
            left: 100px;
        }

        #center {
            margin-left: 500px;
        }

        #head {
            position: absolute;
            top: 30px;
            left: 510px;
            color: rgb(157, 11, 52);
            font-family: cursive;
        }

        #title {
            position: absolute;
            top: 100px;
            left: 600px;
            right: 600px;
            font-size: 25px;
            color: rgb(137, 46, 157);
            font-family: monospace;
        }
        #title2
        {
            position: absolute;
            top: 130px;
            left:810px;
            right: 1200px;
            font-size: 25px;
            color: rgb(165, 34, 95);
            font-family: monospace; 
        }
        #subtitle {
            position: absolute;
            top: 180px;
            left: 510px;
            right: 600px;
            position: absolute;
            font-size:15px;
            font-family: monospace;
            color: rgb(10, 192, 192);

        }

        #edition {
            position: absolute;
            bottom: 50px;
            left: 520px;
            font-size: 20px;
            color: whitesmoke;
        }

        #name {
            position: absolute;
            bottom: 50px;
            left: 1000px;
            font-size: 20px;
            color: cyan;
        }

        #bro {
            bottom: 90px;
            right: 110px;
            left: 960px;
            position: fixed;
            height: 100px;
            border-radius: 50px;
        }
    </style>
</head>

<body>
    <div id="center">

        <img src="ai.png" id="image">
        <img src="me.jpg" alt="bro" id="bro">
        <p id="head">EXPRERTS INSIGHT </p>
        <p id="title">INTRODUCTION TO MACHINE </p>
        <p id="title2">LEARNING</p>
        <p id="subtitle"> Machine learning is a subset of artificial intelligence (AI) that allows computers to learn
            and improve from data without being explicitly programmed</p>
        <p id="edition">SECOND EDITION</p>
        <p id="name">SEC</p>
    </div>

</body>

</html>

```

## OUTPUT:

![alt text](<Screenshot (57).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
