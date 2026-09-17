# Fotografii originale

Fișierele mai mari decât limita mecanismului de încărcare sunt păstrate fără pierderi în subfoldere, împărțite în bucăți de maximum 650.000 de octeți.

Pentru reconstruirea unui original, concatenați piesele în ordine:

```sh
cat original.part01 original.part02 > original.png
```

Pentru un original cu mai multe piese, includeți toate fișierele `original.partNN` în ordine. Numele original, dimensiunea și amprenta SHA-256 sunt în `manifest.json`. Fișierele `*-preview.jpg` sunt copii pentru vizualizare directă și nu înlocuiesc arhiva exactă.
