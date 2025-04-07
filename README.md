# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.
>  - index.HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Linked Script Example</title>
</head>
<body>

  <h1>Hello, World!</h1>
  <button id="greetButton">Click me</button>

  <script src="script.js"></script> <!-- Linking the script.js file -->

</body>
</html>
JS
// script.js

document.getElementById('greetButton').addEventListener('click', function() {
  alert('Hello, welcome to the page!');
});



# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.

Happy Coding! 💻✨
