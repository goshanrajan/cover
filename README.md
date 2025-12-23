# Ex.06 Book Front Cover Page Design
## Date:20/12/25

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
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: linear-gradient(135deg, #333, #000);
      border: 3px solid #555;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.5);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #ffffff;
      text-align: center;
      line-height: 1.3;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
      color: #cccccc;
    }


    .author {
      font-size: 18px;
      text-align: center;
      color: #ffffff;
      margin-top: 20px;
      font-weight: bold;
    }

    .line {
      height: 3px;
      background: linear-gradient(to right, #555, #cccccc);
      width: 60px;
      margin: 10px auto;
      border-radius: 2px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">Mystery & Thriller</div>
      <div class="line"></div>
      <div class="subtitle">A mystery is essentially a search for the truth. It starts with a question: "Who did it?"</div>
    </div>
    <div class="image">
        <img src="Screenshot 2025-12-23 085341.png" length="3%" width="70%">
    </div>
    <div class="author">T.Goshanrajan</div>
  </div>

</body>
</html>
```

## OUTPUT:
<img width="655" height="887" alt="image" src="https://github.com/user-attachments/assets/7c44571c-703b-4786-a6c3-280c05954694" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
