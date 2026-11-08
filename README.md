# kids-games

Jednoduché hry pre deti. Čisté HTML/CSS/JS, bez závislostí a bez build kroku.

## Hry

- [Farebné sudoku](sudoku/) – 4×4 a 5×5, farby namiesto čísel
- [Preskakovaná](preskakovana/) – dosková hra pre dvoch na šachovnici 8×8

## Štruktúra

```
index.html          rozcestník
sudoku/index.html   Farebné sudoku
preskakovana/       Preskakovaná
```

Každá ďalšia hra ide do vlastného priečinka (`<nazov>/index.html`) a pridá sa odkaz do `index.html`.

## GitHub Pages

https://ivann14.github.io/kids-games

## Inštalácia ako aplikácia (PWA)

Hry fungujú aj offline a dá sa pridať na plochu:

- **iPad / iPhone:** otvor hru v Safari → Zdieľať → *Pridať na plochu*.
- **Android / Chrome:** menu → *Inštalovať aplikáciu*.

Po prvom otvorení s internetom ide hra aj bez pripojenia. Pri zmene ikon alebo manifestu zvýš `VERSION` v `sw.js` danej hry.
