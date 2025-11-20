# Ex.06 Book Front Cover Page Design
## NAME: Gayathri D
## REG: 212224220028

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
<title>Book Cover</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="cover">
<div class="border">


<h1>THE DATABASE<br>MANAGEMENT</h1>

<p class="sub">The Science of storing and retrieving information<br>Top seller of 2025</p>

<div class="left">
<h4>SPECIAL EDITION<br></h4>
<div class="name">
<p>   ABILASHA R(25015770)</p>

<div class="right">
<img src="nin.jpg" alt="Author Photo">
<hr class="line">
<div class="class">
<p>SEC</p>
</div>
</div>

</div>
</div>
</div>
</div>
</div>
</div>
</body>
</html>
body {
    background-color: #f2f2f2;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.cover {
    width: 400px;
    height: 550px;
    background: url(hinn.jpg);
    background-size: cover;
    background-position: center;
    position: relative;
    text-align: center;
    color: rgb(88, 69, 69);
    font-family: 'Times New Roman', sans-serif;
    box-shadow: 0 10px rgba(0, 0, 0, 0.3);
}
{
    font-family: 'Times New Roman', sans-serif;
    box-shadow: 0 0 10px rgba(0,0,0,0.3);
}

.border {
    border: 2px solid rgb(240, 23, 117);
    margin: 2px;
    height: 85%;
    padding: 10px;
    position: relative;
}

.top {
    position: relative;
    bottom: 20px;
    right: 120px;
    margin: 0;
    padding: 6px 8px 6px 0;
    display: inline-block;
    font-size: 16px;
    border-bottom: 1px solid rgb(23, 223, 83);
    color: solid red;
}

h1 {
    font-size: 24px;
    margin-top: 30px;
    font-weight: bold;
}

.sub {
    font-style: italic;
    font-size: 15px;
    margin-top: 20px;
}
.left h4 {
    position: relative;
    top: 200px;
    right: 90px;
    font-size: 20px;
    font-style: unset;
    font-weight: bold;
    margin: 0;
}

.left p {
    position: relative;
    top: 240px;
    right: 100px;
    font-size: 20px;
    margin-top: 5px;
}

.right img {
    position: relative;
    top: 5px;
    left: 100px;
    width: 130px;
    height: 150px;
    border: 2px solid rgb(231, 5, 148);
}

.line {
}
.line {
    height: 2px;
    width: 100%;
    background-color: #edd607;
}

.right p {
    font-style: initial;
    font-size: larger;
    top: 20px;
    left: 100px;
    margin-top: 5px;
    font-weight: bold;
}
```

## OUTPUT:
![alt text](<Screenshot (88).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
