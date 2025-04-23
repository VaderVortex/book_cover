# Ex.06 Book Front Cover Page Design
# Date:
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
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Team Iron Man Book Cover</title>
      <style>
        body {
          margin: 0;
          padding: 0;
          display: flex;
          justify-content: center;
          align-items: center;
          height: 100vh;
          background-color: #0d0d0d;
          font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .cover {
          width: 420px;
          height: 600px;
          background: linear-gradient(to bottom right, #1f1f1f, #3a3a3a);
          color: #e62e00;
          padding: 30px;
          position: relative;
          display: flex;
          flex-direction: column;
          justify-content: space-between;
          box-shadow: 0 0 25px rgba(230, 46, 0, 0.4);
          border-radius: 10px;
          border: 2px solid #e62e00;
        }
        .tagline {
          font-size: 0.9rem;
          color: #e62e00;
          text-transform: uppercase;
          border-left: 4px solid #e62e00;
          padding-left: 10px;
          margin-bottom: 20px;
        }
        h1 {
          font-size: 2rem;
          margin: 0;
          line-height: 1.2;
          color: #fff;
        }
        .subtitle {
          font-size: 0.9rem;
          color: #ffb380;
          margin-top: 10px;
          font-style: italic;
        }
        .wave {
          width: 100%;
          height: auto;
          margin: 30px 0;
          border-radius: 5px;
        }
        .edition {
          font-size: 1rem;
          color: #e62e00;
          font-weight: bold;
          text-transform: uppercase;
          margin-bottom: 20px;
        }
        .footer {
          display: flex;
          justify-content: space-between;
          align-items: center;
          font-size: 1rem;
          color: #f5f5f5;
        }
        .author-img {
          position: absolute;
          bottom: 20px;
          right: 20px;
          width: 80px;
          height: 80px;
          object-fit: cover;
          border: 2px solid #e62e00;
          border-radius: 6px;
        }
        .goofy {
          font-size: 0.85rem;
          color: #f5f5f5;
          margin-top: 15px;
          font-weight: bold;
        }
      </style>
    </head>
    <body>
      <div class="cover">
        <div>
          <div class="tagline">Stark Industries</div>
          <h1>Team Iron Man<br></h1>
          <div class="subtitle">Genius, Billionaire, Playboy, Philanthrophist</div>
          <img class="wave" src="c:\Users\admin\Downloads\6acc34d84a62d06c6492de8c00b6fc1c.jpg" alt="Iron Man" />
          <div class="edition">Special Stark Edition</div>
          <div class="goofy">Cover Page credits: JARVIS</div>
        </div>
        <div class="footer">
          <div class="author">Tony Stark</div>
          <div class="publisher">Stark Labs</div>
        </div>
        <img class="author-img" src="c:\Users\admin\Downloads\943eef75dbff4000794730fd9732f05a.jpg" alt="Iron Man photo" />
      </div>
    </body>
    </html>

# OUTPUT:
![image](https://github.com/user-attachments/assets/5f91c6f7-32a8-48c8-a366-cf05c58e45c9)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
