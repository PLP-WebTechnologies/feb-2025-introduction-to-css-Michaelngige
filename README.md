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
    <title>Styled Web Page</title>
    <link rel="stylesheet" href="styles.css"> <!-- Linking External CSS -->
</head>
<body>

    <header>
        <h1 class="title">Welcome to My Styled Page</h1>
    </header>

    <section class="content">
        <img src="https://via.placeholder.com/300" alt="Sample Image" class="styled-image">

        <p id="description">
            This is a simple demonstration of applying CSS styling using an external stylesheet.
        </p>
    </section>

    <footer>
        <p class="footer-text">© 2025 My Website. All rights reserved.</p>
    </footer>

</body>
</html>
