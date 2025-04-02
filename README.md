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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styling with CSS</title>
    <!-- Link to external CSS file -->
    <link rel="stylesheet" href="plpstyles.css">
</head>
<body>

    <!-- Header Section -->
    <header id="header">
        <h1>Welcome to My Website</h1>
    </header>

    <!-- Main Content Section -->
    <div class="main-content">
        <h2>About This Page</h2>
        <p>This page is styled using an external CSS file.It is a declaration of my never ending love for you</p>
        <img src="Pink Lily of the Valley | Buy Online at Nature Hills Nursery https://images.app.goo.gl/DsQdmXf38nKcCEYD7" alt="Placeholder Image">
        <p>Here's a simple button for you to click:</p>
        <button class="button">Click Me</button>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>Made with ❤️ by Precious</p>
    </footer>

</body>
</html>




/* Global Styles */
body {
    font-family: 'Arial', sans-serif; /* Default font */
    background-color: #f4f4f4; /* Light gray background */
    color: #333; /* Dark text color for readability */
    margin: 0;
    padding: 0;
}

/* Header styling using ID selector */
#header {
    background-color: #4CAF50; /* Green background */
    color: white; /* White text */
    text-align: center;
    padding: 20px 0; /* Padding top and bottom */
    margin-bottom: 30px; /* Margin below the header */
}

/* Styling the main content using class selector */
.main-content {
    padding: 20px; /* Padding inside the content area */
    margin: 0 10px; /* Margins on the left and right */
    background-color: white; /* White background for the content */
    border-radius: 8px; /* Rounded corners for the content */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
}

/* Styling for images */
img {
    max-width: 100%; /* Ensure the image is responsive */
    height: auto; /* Maintain aspect ratio */
    border: 5px solid #ddd; /* Light gray border around the image */
    padding: 5px; /* Padding inside the image border */
    border-radius: 8px; /* Rounded corners for the image */
    margin-top: 20px; /* Margin above the image */
}

/* Link styling using a pseudo-class selector */
a:hover {
    color: #4CAF50; /* Change link color on hover */
    text-decoration: underline; /* Underline on hover */
}

/* Button styling using class selector */
.button {
    background-color: #4CAF50; /* Green background */
    color: white; /* White text */
    padding: 10px 20px; /* Padding inside the button */
    border: none; /* Remove border */
    border-radius: 5px; /* Rounded corners */
    cursor: pointer; /* Pointer cursor on hover */
    margin-top: 20px; /* Margin above the button */
}

.button:hover {
    background-color: #45a049; /* Darker green on hover */
}





