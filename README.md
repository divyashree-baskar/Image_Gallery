# Ex.08 Design of Interactive Image Gallery
DATE:16/05/2025
NAME:DIVYASHREE B
REG NO.:212224040081
## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Interactive Image Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f4;
    }

    h1 {
      margin-bottom: 30px;
      font-size: 36px;
      font-weight: bold;
      text-transform: uppercase;
      color: #333;
    }

    .gallery {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }

    .gallery img {
      width: 250px;
      height: 400px;
      object-fit: cover;
      cursor: pointer;
      border: 4px solid #ccc;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, border-color 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
      border-color: #333;
    }
  </style>
</head>
<body>
  <h1>Interactive Image Gallery</h1>
  <div class="gallery">
    <img src="coffee.1.jpg" alt="Image 1" />
    <img src="coffee.2.jpg" alt="Image 2" />
    <img src="coffee.3.jpg" alt="Image 3" />
    <img src="coffee.4.jpg" alt="Image 4" />
    <img src="coffee.5.jpg" alt="Image 5" />
    <img src="coffee.6.jpg" alt="Image 6" />
  </div>
</body>
</html>

```

## OUTPUT
![alt text](<divya/imageapp/static/Screenshot 2025-05-16 225007.png>)


## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
