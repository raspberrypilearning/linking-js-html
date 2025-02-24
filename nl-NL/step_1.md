Om JavaScript-bestanden aan een HTML-document te koppelen, voeg je een `<script>`-element toe met een `src`-kenmerk ingesteld op de naam van het JavaScript-bestand.

Je zou het `<script>` element moeten plaatsen vlak voor de sluitende `</body>` tag omdat je mogelijk alle HTML-inhoud op de pagina nodig hebt om te laden voordat je de JavaScript-functies uitvoert.

--- code ---
---
language: html
filename: 
line_numbers: true
---

  <body>
    <!-- HTML-inhoud -->

    <script src="scripts.js"></script>

  </body>

--- /code ---
