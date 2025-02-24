To link JavaScript files to an HTML document, you add a `<script>` element with an `src` attribute set to the name of the JavaScript file.

Tu dois placer l'élément `<script>` juste avant la balise de fermeture `</body>`, car il peut être nécessaire que tout le contenu HTML de la page soit chargé avant l'exécution des fonctions JavaScript.

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
