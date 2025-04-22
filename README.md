# Ex.06 Book Front Cover Page Design
# Date:22.04.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #3906d172;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 350px;
      height: 550px;
      background-image: url('book.jpg'); 
      background-size: cover;
      background-position: center;
      box-shadow: 0 10px 30px rgb(0, 0, 0);
      position: relative;
      border: 5px solid #4e47df;
    }

    .overlay {
        position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); 
  text-align: center;
  border-radius: 10px;
}
    .title {
      font-size: 26px;
      font-weight:bold;
      color: #bcc20f;
      margin: 0;
      text-align:justify;
      font-family:cursive;
      padding: top 60px;
    }

    .subtitle {
      font-size: 13px;
      color: #ffc579;
      margin-top:10px;
      align-self: auto;
      padding-bottom: 20%;
      /* font-style: italic; */
      font-family: Georgia, 'Times New Roman', Times, serif;
    }

    .author {
      font-size:medium;
      font-family: Verdana, Geneva, Tahoma, sans-serif;
      color: #ffffff;
      margin-top: 90px;
    }
    .bookimage{
        max-width: 100px;
        max-height: 300px;
        border-radius: 50%;
        margin-bottom: auto;
        margin-right: auto;
        margin:auto;
        align-self:flex-end;
        align-content: end;


    }
  </style>
</head>
<body>

  <div class="book-cover">
    <div class="overlay">
      <h1 class="title">NEVER ENDING SKY</h1>
      <p class="subtitle">Best selling author of ordinary life</p>
      <img src="images.jpg" class="bookimage"/>
      <p class="author"> -JOSEPH KIRKLAND </p>
    </div>
  </div>

</body>
</html>
```
# OUTPUT:
![Screenshot 2025-04-22 132556](https://github.com/user-attachments/assets/30b731cc-3cfd-4780-b2fb-c0f4deda38c7)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
