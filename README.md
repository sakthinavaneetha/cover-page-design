# Book CoverPage Design

## AIM:
To design a static web site for a book cover page.
![AIM](./image/reference.png)
### Step 1:
Create a new project and a app for your project. Create templates for your web application to display image. 

### Step 2:
Now write the appropiate html code and css code.

### Step 3:
Provide proper margins and padding to display it in proper way.

### Step 4:
Then create appropiate views for your templates and provide the urls for them in urls.py.Now run the server to use your web application and see the result.


## PROGRAM :
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 50px;
            font-family: 'Franklin Gothic Heavy', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/bg.jpeg);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Franklin Gothic Heavy', monospace;
            font-size: 25px;
            text-align: left;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:T'Franklin Gothic Heavy';
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 175px;
            left: 300px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="/static/images/photo.jpeg" width="100" height="110" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Sakthi Navaneetha</b></p>
            </div>
            <div class="publisher">
                PACKT
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>

## OUTPUT:
![OUTPUT](./image/coveroutput.png)
![OUTPUT](./image/covervalidation.png)

## Result:
Thus a book cover has been successfully created using HTML and CSS.

