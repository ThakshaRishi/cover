# Ex.06 Book Front Cover Page Design
## Date:30.11.2023

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
<!DOCTYPE html>
<html>

<head>
    <title>CYBER SECURITY</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cybersec.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:90px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:white;
            top:240px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 5px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:240px;
            
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:200px;
            left:350px;
        }
        .ed{
            color:azure;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:145px;
        
        }
        .subtitle{
            color:white;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top:220px;
            left: 290px;
            width: 100px;
            height: 70px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                Encrypt the Present, Secure the Future
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>A Cyber Security Odyssey</h1></div>
            <div class="subtitle">
                 Securing Cyberspace
            </div>
            <div class="subtitle">
                Top seller of 2023

            </div>

            <div class="mypic">
                <img src="thaksha.jpg " width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>THAKSHA RISHI</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:

![Alt text](<Screenshot 2023-11-30 131826.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
