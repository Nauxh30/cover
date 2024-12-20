# Ex.06 Book Front Cover Page Design
## Date: 8-12-2024

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Web Design</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #1c1c1c;
      color: white;
    }

    .container {
      width: 600px;
      margin: 50px auto;
      padding: 20px;
      background: #333;
      position: relative;
      border-radius: 10px;
    }

    .expert {
      color: orange;
      font-size: 14px;
      text-align: left;
    }

    h1 {
      margin: 20px 0;
      font-size: 30px;
      text-align: left;
      line-height: 1.2;
    }

    h1 span {
      display: block;
      font-weight: bold;
    }

    .description {
      font-size: 14px;
      margin: 20px 0;
      line-height: 1.5;
      text-align: left;
    }

    .bottom-section {
      position: absolute;
      bottom: 20px;
      left: 20px;
    }

    .edition {
      color: orange;
      font-size: 18px;
      text-align: left;
    }

    .author {
      font-size: 20px;
      margin-top: 10px;
      text-align: left;
    }

    .logo {
      font-size: 20px;
      font-weight: bold;
      color: white;
      position: absolute;
      bottom: 20px;
      right: 20px;
    }

    .wave {
      display: block;
      width: 100%;
      margin: 20px 0;
    }

    .author-photo {
      position: absolute;
      bottom: 20px;
      right: 20px;
      width: 80px;
      height: 80px;
      border-radius: 50%;
      border: 3px solid white;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="expert">EXPERT INSIGHT</div>
    <h1>
      Responsive Web Design<br>
      <span>with HTML5 and CSS</span>
    </h1>
    <div class="description">
      Develop future-proof responsive websites<br>
      using the latest HTML5 and CSS techniques
    </div>
    <img class="wave" src="C:\Users\naush\Downloads\rb_76.png" alt="Wave">
    <div class="bottom-section">
      <div class="edition">Third Edition</div>
      <div class="author">Ben Frain</div>
    </div>
    <img class="author-photo" src="C:\Users\naush\OneDrive\Desktop\ben.jpg" alt="Author Photo">
    <div class="logo">Packt</div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (178).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
