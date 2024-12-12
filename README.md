# Ex.06 Book Front Cover Page Design
# Date:12/11/2024
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

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Compact Book Cover</title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="book-cover">
            <h3 class="header">Top Bestseller</h3>
            <div class="title">
                <h1>The Tale of Dreams</h1>
            </div>
            <div class="author">by Jane Doe</div>
        </div>
    </body>
    </html>
    
    body {
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f7f9fc;
        font-family: 'Arial', sans-serif;
    }
    
    .book-cover {
        width: 250px;
        height: 350px;
        background: url('cover1.jpg') no-repeat center center;
        background-size: cover;
        border: 2px solid #454215;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        text-align: center;
        padding: 10px;
        box-shadow:  0 4px 6px rgba(238, 235, 29, 0.708);
    }
    
    .header {
        font-size: 14px;
        font-weight: bold;
        color: #ffffff;
        background: rgba(0, 0, 0, 0.5);
        padding: 5px 10px;
        border-radius: 5px;
    }
    
    .title h1 {
        font-size: 20px;
        color: #ffffff;
        margin: 0;
        text-shadow: 0 2px 4px rgba(0, 0, 0, 0.7);
    }
    
    .author {
        font-size: 14px;
        color: #ffffff;
        text-shadow: 0 2px 4px rgba(0, 0, 0, 0.7);
    }

# OUTPUT:

![image](https://github.com/user-attachments/assets/c074049f-5d6c-4701-b278-b774fa780d34)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
