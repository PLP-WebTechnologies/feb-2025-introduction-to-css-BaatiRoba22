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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction to CSS</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to external CSS file -->
</head>
<body>
    <header>
        <h1>Introduction to CSS</h1>
    </header>

    <main>
        <!-- Objectives Section -->
        <section id="objectives">
            <h2>Objectives</h2>
            <ol>
                <li>Link an external CSS file to an HTML document.</li>
                <li>Apply basic styling using selectors.</li>
                <li>Use colors, fonts, and spacing effectively.</li>
            </ol>
        </section>

        <!-- Sample Content Section -->
        <section id="content">
            <h2>CSS Styling Examples</h2>
            <p class="description">In this exercise, we will style elements with different CSS properties!</p>
            <img src="https://images.pexels.com/photos/3770581/pexels-photo-3770581.jpeg" alt="Example Image" class="styled-image">
            <p>Apply styles using classes, IDs, and type selectors.</p>
        </section>
    </main>

    <footer>

    </footer>
</body>
</html>
css
/* style.css */

/* 1. Type selector */
body {
    font-family: Arial, sans-serif; /* Use a readable font */
    line-height: 1.6; /* Improve line height for readability */
    margin: 0;
    padding: 0;
}

/* 2. ID selector */
# objectives {
    background-color: #f8f9fa; /* Light background color */
    padding: 20px; /* Padding for spacing */
    border: 2px solid #007bff; /* Border for visual separation */
    border-radius: 5px; /* Rounded corners */
}

/* 3. Class selector */
.description {
    color: #333; /* Dark gray text color for description */
    font-size: 1.2em; /* Larger font size for emphasis */
}

/* Style an image */
.styled-image {
    max-width: 100%; /* Responsive image */
    height: auto; /* Maintain aspect ratio */
    border: 2px solid #007bff; /* Border around image */
    border-radius: 10px; /* Slightly rounded corners */
    margin: 20px 0; /* Margin for spacing
Happy Coding! 💻✨
