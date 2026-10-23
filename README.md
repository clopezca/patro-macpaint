# El patró que va sobreviure

Línia de temps interactiva de la PAC 1 de _Cultura digital_ (UOC): _MacPaint, Susan Kare i el llenguatge visual de la informàtica per a tothom_.

Feta amb [Timeline.js](https://timeline.knightlab.com/) (Knight Lab) i publicada amb GitHub Pages.

## Fitxers

- `index.html`: carrega Timeline.js i el contingut.
- `timeline.json`: les tretze fites (text, dates, grups i fonts).
- `styles.css`: estils propis amb estètica MacPaint.

## Veure-ho en local

Timeline.js carrega el JSON amb `fetch`, per tant cal un servidor local (no funciona obrint `index.html` directament):

```
python3 -m http.server
```

i obrir `http://localhost:8000`.
