# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:
Create an app in the Django interface.
### Step 3:
Create a folder named 'static' in the app floder.
### Step 4:
Create a new HTML files in the static folder.
### Step 5:
Write the HTML code with relevant CSS properties
### Step 6:
Choose the appropriate style and color scheme.
### Step 7:
Insert rhe images in their appropriate places.
### Step 8:
publish the website in the localHost.

## Code:
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(255, 255, 255) and rgb(212, 158, 212);
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(book.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(161, 151, 151);

        }

        
        .hrstyle{
            width:245px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(160, 135, 144);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:160px;
        }
        .ed{
            color: rgb(252, 252, 252);
            font-size: large;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 115px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SAVEETHA ENGINEERING COLLEGE
            </div>
            <div class="hrstyle">
                <hr style="color: purple;">
            </div>
            <div class="booktitle">
                <h1>FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT</h1></div>
            <div class="SEC">
             HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="IMAGE EX06.jpeg" width="110" height="100" alt=>
            </div>
            <div class="id">
                <hr style="color: rgb(255, 255, 255);">
            </div>
            <div class="author">
               <p><b>BHARATHI M K</b></p>
            </div>
            <div class="pub">
                COMPUTER SCIENCE AND ENGINEERING
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>

## Output:




![Screenshot from 2023-12-20 15-53-20](https://github.com/BHARATHI20MK/cover-page-design/assets/147474125/18d2263e-ebad-41ba-9299-dfd41e050da2)


## Result:
The program for designing book front cover page using HTML and CSS is completed successfully
