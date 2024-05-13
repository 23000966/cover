# Ex.06 Book Front Cover Page Design
## Date:

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
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgb(200, 77, 52);
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 650px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url('https://static.vecteezy.com/system/resources/previews/010/008/086/non_2x/background-dimension-3d-graphic-message-board-for-text-and-message-design-line-shadow-for-modern-web-design-free-vector.jpg') ;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(0, 5, 10);
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(28, 25, 2);
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(28, 8, 3);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: rgb(0, 10, 3);
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: rgb(8, 123, 31);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:gold(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: rgb(3, 3, 1);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>COMPUTER NETWORKS</b>
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(218, 246, 9)">
            </div>
            <div class="booktitle">
                <h1><b>PHYSICS  FOR QUANTUM COMPUTING</b></h1></div>
            <div class="subtitle">
                 <b>INTRODUCING QUANTUM COMPUTING</b> 
            <div class="subtitle2">
                <b>>> Small shifts in your thinking, and small changes in your energy</b><br>
                <b>>> used in the quantitative analysis of cellular antigen expression.</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="c:\Users\admin\Downloads\WhatsApp Image 2024-05-13 at 09.36.36_2d8c00d7.jpg" width="100" height="90" >
            </div>
            <div class="id">
                <hr style="color:rgb(1, 0, 8)">
            </div>
            <div class="author">
               <p><b>SANTHOSH KUMAR R(212223240153)</b></p>
            </div>
            <div class="pub">
                SEC 27'
            </div>
        </div>
    </div>
</body>
</html>
    </html>    
```

## OUTPUT:
![image](https://github.com/23000966/cover/assets/153983364/f863f2aa-60f9-4d8e-9603-705d50eb9377)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
