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
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>MY BOOK</title>

<style>
/* CENTER THE BOOK */
body {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;   /* horizontal center */
    align-items: center;       /* vertical center */
    height: 100vh;
    background: #c9c7c7;
}

/* BOOK COVER */
#book {
    width: 500px;
    height: 700px;
    background-image: url('image.png');
    background-size: cover;
    border: 5px solid rgb(192, 180, 204);
    border-radius: 18px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    text-align: center;
}

/* TITLE */
#book h1 {
    margin-top: 40px;
    font-size: 48.5px;
    color: rgb(127, 101, 154);
}

/* SUB TEXT */
#book p {
    font-size: 11px;
}

/* AUTHOR */
#book h2 {
    font-size: 17.5px;
}
</style>
</head>

<body>

<div id="book">
    <h1>STAY WITH ME</h1>
    <p>STILL .....</p>
    <h2>AYOBAMI  ADEBAYO</h2>
</div>

</body>
</html>
```




## OUTPUT:
<img width="1906" height="955" alt="stwm" src="https://github.com/user-attachments/assets/0ae6b41e-23a4-4103-b5ef-4554a78df4c4" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
