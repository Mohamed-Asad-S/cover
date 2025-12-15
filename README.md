# Ex.05 Book Cover Page Design
## Date:15.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

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
hello.html

<html>
    <head>
        <title>book cover</title>
        <link href="cello.css" rel="stylesheet">
    </head>
    <body>
        <div class="cover">
            <h1>about the book</h1>
            <hr>
        <p>"<p2>The Fundamentals of C Programming</p2>" is a beginner-friendly guide designed to introduce readers to the core concepts of the C language in a clear and simple way. This book explains basic programming ideas such as data types, variables, operators, control statements, functions, arrays, and pointers with easy examples and step-by-step explanations. Written in simple language, it helps students build strong logical thinking and problem-solving skills. Ideal for beginners and learners in computer science, this book lays a solid foundation for understanding programming and prepares readers for advanced concepts in software development.</p>
        </div>
       <div class="box">
        " C is the foundation language that builds strong programmers. "
       </div>
       <div class="container">
        <p3>Mohamed Asad S is a dedicated computer science educator with extensive experience in teaching C programming. With a passion for simplifying complex concepts, the author focuses on building strong programming fundamentals and problem-solving skills among beginners.</p3>
       </div>
       <div class="price">
        <p4>SEC Publishers</p4><p></p>
            <p5>Printed in India</p5>
            <p6>Price: &#8377;399</p6>

       </div>
    </body>
</html>

cello.html

body{
    background-image: url("bg.png");
    background-repeat: no-repeat;
    background-size: contain;
    margin-left: 550px;
    margin-right: 550px;
    background-position: center;
    color: white;
}

p>p2
{
    background-color: goldenrod;
}


.box {
    padding:10px;
    height: 65px;
    width: 400px;
    font-size: 20px;
    border-left:black 4px solid;
    background-color: black;
    font-style:italic;
    border-radius: 15px;
}
.container
 {
    background-image: url("my pic.png");
    background-repeat:no-repeat;
    background-size: contain;
    background-position: 15px 15px;
    background-size: 80px 80px;
    margin-top: 15px;
    padding:10px;
    height: 100px;
    font-size: 18px;
    background-color:green;
    font-style:italic;
    padding-left: 100px;
    border: 15px;
    font-size:small;
}
.price {
    margin-top:80px;
    padding:10px;
    height: 60px;
    color:yellow;
    font-size: 18px;
    background-color: darkblue;
}
p6
{
    margin-left:200px;
}

```

## OUTPUT:

![alt text](<Screenshot 2025-12-15 145355.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
