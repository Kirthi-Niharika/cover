# Ex.06 Book Front Cover Page Design
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
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Verdana', 'sans-serif','Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bookcover.png);
            background-size: cover;
        }
            

        .insight{
            color: white;
            font-size: 10px;
        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        

            position: relative;
            color: white;
            top:180px;
            margin-left: 20px;
            
            font-family:Georgia;
            font-size: large;
        }
        .booktitle{
            font-family: Verdana, sans-serif;
            font-size: larger;
            position: relative;
            top: 30px;
            margin-left: 20px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: 30px;
            position: relative;
            top:130px;
            left:270px;
        }
        .ed{
            color: red;
            font-size: large;
            font-family: Verdana;
            position:relative;
            top:50px;
            margin-left: 20px;

        }
        .subtitle{
            font-family:Verdana;
            font-size: small;
            position: relative;
            top:40px;
            margin-left: 20px;

        }
        .mypic{
            position: relative;
            top: 125px;
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
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: orangered;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web  Design with HTML5 and CSS</h1></div>
            <div class="subtitle">
                <b>Develop future-proof responsive websites using the latest HTML5 and CSS techniques     </b>       </div>
            <div class="mypic">
                <img src="prof.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orangered;">
            </div>
            <div class="author">
               <p><b>Ben Frain</b></p>
            </div>
            <div class="pub">
               <b><u>Packt></u></b>
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>
        </div>
    </bodY>
</html>
```

## OUTPUT:
<img width="952" alt="exp6" src="https://github.com/Kirthi-Niharika/cover/assets/114135005/ade3b4f5-7ba1-4f59-9280-d194b30a6b70">


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
