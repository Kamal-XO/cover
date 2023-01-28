# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the github repository and create a django admin interface
### Step 2:
Write HTML and CSS for designing book cover page and execute them .
### Step 3:
Validate the HTML and CSS code.
### Step 4:
Publish the website in the given URL.

## Code:
```
cover.html

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(0, 159, 212);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/bok.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(106, 37, 255);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(44, 29, 44);
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
            color:orange;
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
            top: 100px;
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
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>LIFESTYLE ADVICE FOR BEING SUCCESFULL</h1></div>
            <div class="subtitle">
                
            </div>
            <div class="mypic">
                <img src="/static/images/my.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(40, 31, 47);">
            </div>
            <div class="author">
               <p><b></b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b></b>
            </div>
        </div>
    </body>
</html>

```

## Output:

![output](./bak.png)

## HTML VALIDATION :

![output](./htvl.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully
