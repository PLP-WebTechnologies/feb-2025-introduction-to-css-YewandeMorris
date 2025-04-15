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

/* ID selector - main heading */
#main-heading {
  color: #2c3e50;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  text-align: center;
  margin: 40px 0 20px;
  font-size: 2.5em;
}

/* Class selector - card container */
.card {
  max-width: 600px;
  margin: 20px auto;
  padding: 25px;
  border: 2px solid #3498db;
  border-radius: 10px;
  background-color: #f9f9f9;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  font-family: 'Open Sans', sans-serif;
}

/* Element selector - paragraph */
p {
  color: #555;
  font-size: 1.1em;
  line-height: 1.8;
}

/* Style the image */
img.featured {
  width: 100%;
  max-width: 100%;
  height: auto;
  border: 4px solid #8e44ad;
  padding: 8px;
  margin-top: 20px;
  border-radius: 12px;
  display: block;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Styled Web Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-heading">Welcome to My Stylish Page</h1>

  <div class="card">
    <p>
      This page demonstrates the use of different CSS selectors, including IDs, classes, and elements. 
      We've also added spacing, borders, and typography to enhance the aesthetics and readability.
    </p>
    <img src="your-image.jpg" alt="A beautiful view" class="featured">
  </div>

</body>
</html>

/* ID selector - main heading */
#main-heading {
  color: #004e64;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  text-align: center;
  margin: 40px 0 20px;
  font-size: 2.8em;
  background: linear-gradient(to right, #00c6ff, #0072ff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

/* Class selector - card container */
.card {
  max-width: 700px;
  margin: 30px auto;
  padding: 30px;
  border: 2px solid #00a8cc;
  border-radius: 12px;
  background-color: #e0f7fa;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
  font-family: 'Open Sans', sans-serif;
}

/* Element selector - paragraph */
p {
  color: #003f5c;
  font-size: 1.1em;
  line-height: 1.8;
}

/* Image styling */
img.featured {
  width: 100%;
  max-width: 100%;
  height: auto;
  border: 4px solid #0096c7;
  padding: 10px;
  margin-top: 20px;
  border-radius: 14px;
  display: block;
}

/* Body styling for background and padding */
body {
  background: linear-gradient(to bottom, #caf0f8, #90e0ef);
  margin: 0;
  padding: 20px;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ocean Awareness Project</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-heading">Protect Our Oceans</h1>

  <div class="card">
    <p>
      Every year, millions of tons of waste find their way into our oceans. This platform raises awareness, shares data, 
      and empowers individuals to take action. Together, we can protect marine life and preserve our planet.
    </p>
    <img src="ocean-image.jpg" alt="Clean ocean with coral reefs" class="featured">
  </div>

</body>
</html>
