To link JavaScript files to an HTML document, you can use the `<script>` tag.

You can either place the `<script>` element inside the `<head>` element.

--- code ---
---
language: html
filename: index.html
line_numbers: true
---

    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>External Script Example</title>
      <!-- Linking external JavaScript file -->
      <script src="script.js"></script>
    </head>

--- /code ---

--- /task ---

Or you can place the `<script>` element just before the closing `</body>` tag. 

This method is best if you need all the HTML content on the page to load before running the JavaScript functions.

--- code ---
---
language: html
filename: index.html
line_numbers: true
---

    <body>
      <!-- HTML content -->
      <h1>This is the body of the document</h1>
      <!-- Linking external JavaScript file within the body -->
      <script src="script.js"></script>
    </body>

--- /code ---

--- /task ---