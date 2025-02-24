To link JavaScript files to an HTML document, you add a `<script>` element with an `src` attribute set to the name of the JavaScript file.

Je zou het `<script>` element moeten plaatsen vlak voor de sluitende `</body>` tag omdat je mogelijk alle HTML-inhoud op de pagina nodig hebt om te laden voordat je de JavaScript-functies uitvoert.

## --- code ---

language: html
filename:
line_numbers: true
-------------------------------------------------------

  <body>
    <!-- HTML content -->

```
<script src="scripts.js"></script>
```

  </body>

\--- /code ---
