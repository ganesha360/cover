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
```html
<style>
    .bookpage{
        width: 400px;
        height: 600px;
        background-color: #3d3a3a;
        color:white;
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(/static/images/backimage.jpg);
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
        color:lightblue;
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
    .publisher{
        font-size: medium;
        position: relative;
        top:155px;
        left:330px;
    }
    .edition{
        color:white;
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
    .photo{
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
            <img src="/static/images/myimage.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: white;">
        </div>
        <div class="author">
           <p><b>GANESH R</b></p>
        </div>
        <div class="publisher">
            Packt>
        </div>
        <div class="edition">
            <b>First Edition</b>
        </div>
        
    </div>
</body>
```
## CLIENT OUTPUT:
![OUTPUT](./BC1.png)
## SETVER OUTPUT:
![OUTPUT](./BC2.png)
## HTML VALIDATOR:
![OUTPUT](./BC3.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
