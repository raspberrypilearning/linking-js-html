Pour lier des fichiers JavaScript à un document HTML, ajoute un élément `<script>` avec un attribut `src` défini sur le nom du fichier JavaScript.

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
