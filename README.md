# Ex.06 Book Front Cover Page Design
## Date:4-11-2023
## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
Developed by:ALAGU NACHIYAR K
Reg no:212222240006
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(/static/images/bg.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(240, 81, 227);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(195, 255, 0);
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
            left:330px;
        }
        .ed{
            color: rgb(232, 77, 224);
            font-size: medium;
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
            top: 135px;
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
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(74, 190, 232);">
            </div>
            <div class="booktitle">
                <h1>THE COMPLETE GUIDE TO YOUR NEW APP </h1></div>
            <div class="subtitle">
                with Django and Bootstrap Insights
            </div>
            <div class="mypic">
                <img src="/static/images/butter.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(230, 30, 153);">
            </div>
            <div class="writer">
               <p><b>ALAGU NACHIYAR K </b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </bodY>
</html>
```
## OUTPUT:
![image](https://github.com/Nachiyarr/cover/assets/113497340/9af0bae6-4abd-487b-ba38-7613142f332e)





## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
