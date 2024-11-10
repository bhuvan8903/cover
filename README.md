# Ex.06 Book Front Cover Page Design
## Date:10/11/24

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
DEVELOPED BY: Bhuvaneshwaran H
REG.NO:212223240018
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SOUL</title>
    <style>
        .box {
            height: 700px;
            width: 500px;
            margin: auto;
            position: relative;
            border: 1px solid #ccc;
        }

        .title {
            font-size: xx-large;
            font-weight: 400;
            font-style: italic;
            top: 0%;
            left: 10%;
            color: rgb(25, 165, 57);
            position: absolute;
        }

        .caption {
            font-size: x-large;
            font-weight: 1000;
            font-style: oblique;
            color: black;
            top: 40%;
            right: 22px;
            position: absolute;
        }

        .author {
            right: 0%;
            bottom: 0px;
            position: absolute;
        }

        .name {
            font-size: large;
            font-weight: 900;
            font-style: initial;
            position: absolute;
            right: 4%;
            bottom: 10%;
            color: rgb(130, 157, 9);
        }

        .bottom-bar {
            position: absolute;
            bottom: 10px;
            left: 20px;
            font-size: medium;
        }

        .publisher,
        .date {
            display: inline-block;
            margin-right: 10px;
            font-weight: 600;
            color: rgb(2, 255, 19);
        }

        .strip {
            width: 100%;
            height: 1px;
            background-color: #000;
            position: absolute;
            bottom: 0;
        }
    </style>
</head>
<body>
    <div class="box">
        <center>
            <!-- Use relative paths for your images or upload them to a server -->
            <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-11-10 210439.png" width="100%" height="100%">
        </center>
        

        <hr>

        <div class="name">
            <p>Bhuvaneshwaran H</p>
        </div>

        <div class="author">
            <!-- Use relative path or valid online URL for the author image -->
            <img src="C:\Bhuvaneshwaran important details\SCL_0648 copy (1).jpg" width="85" height="85">
        </div>

        <div class="bottom-bar">
            <div class="publisher">Publisher: JK Printers</div>
            <div class="date">2024</div>
        </div>

        <div class="strip"></div>
    </div>
</body>
</html>

```
## OUTPUT:
![Screenshot 2024-11-10 163618](https://github.com/user-attachments/assets/7e73a82b-3a61-4066-9b6f-ea7a666c1f4c)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
