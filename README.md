# Ex.06 Book Front Cover Page Design
## Date: 28.04.2025
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
###### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            width: 210mm;
            height: 297mm;
            font-family: "Times New Roman", serif;
            background-color: black;
            color: rgb(19, 9, 9);
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .cover-container {
            position: relative;
            width: 90%;
            height: 90%;
            background: url('background.jpg') no-repeat center center/cover;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 20px;
            box-shadow: 0 0 10px rgba(64, 58, 58, 0.8);
        }

        .top-section {
            text-align: left;
        }

        .expert-insight {
            font-size: 1rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 1px;
            border-left: 4px solid orange;
            padding-left: 8px;
            margin-bottom: 10px;
        }

        .book-title {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .bottom-section {
            background-color: rgba(0, 0, 0, 0.7);
            color: black;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }

        .bottom-section .details {
            text-align: left;
            font-size: 1rem;
        }

        .edition {
            color: orange;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .author {
            color: rgb(72, 154, 88);
            font-size: 1.2rem;
            font-weight: bold;
        }

        .author-photo {
            width: 120px;
            height: 120px;
            border-radius: 10%;
            border: 2px solid white;
        }

        .publisher-logo {
            max-width: 100px;
        }
    </style>
</head>
<body>
    <div class="cover-container">
        <div class="top-section">
            <div class="expert-insight">Expert Insight</div>
            <div class="book-title">Responsive Web Design with HTML5 and CSS</div>
            <div class="subtitle">Develop future-proof responsive websites using the latest HTML5 and CSS techniques</div>
        </div>
        <div class="bottom-section">
            <div class="details">
                <div class="edition">Limited Edition</div>
                <div class="author">SITHARTH B S</div>
            </div>
            <div>
                <img src="me.jpg" alt="Author Photo" class="author-photo">
            </div>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![Screenshot 2025-05-26 212537](https://github.com/user-attachments/assets/43ce3ed2-d679-4c7a-aa06-a62e41e9c569)




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
