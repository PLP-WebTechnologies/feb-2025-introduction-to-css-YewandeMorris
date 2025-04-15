# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

/* ID selector */
#main-heading {
  color: #2c3e50;
  font-family: 'Georgia', serif;
  text-align: center;
  margin-bottom: 20px;
}

/* Class selector */
.card {
  border: 2px solid #3498db;
  padding: 20px;
  margin: 20px;
  background-color: #ecf0f1;
  font-family: 'Arial', sans-serif;
}

/* Element selector */
p {
  color: #34495e;
  line-height: 1.6;
}

/* Image styling */
img.featured {
  width: 100%;
  max-width: 400px;
  border: 5px solid #8e44ad;
  padding: 10px;
  margin: 20px auto;
  display: block;
  border-radius: 10px;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Styled HTML Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-heading">Welcome to My Styled Page</h1>

  <div class="card">
    <p>This is a simple card with some text. It uses margins, paddings, a border, and a different font for styling.</p>
    <img src="your-image.jpg" alt="A featured image" class="featured">
  </div>

</body>
</html>


