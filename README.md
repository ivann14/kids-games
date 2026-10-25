# kids-games

Jednoduché hry pre deti. Čisté HTML/CSS/JS, bez závislostí a bez build kroku.

## Hry

- [Farebné sudoku](sudoku/) – 4×4 a 5×5, farby namiesto čísel

## Štruktúra

```
index.html          rozcestník
sudoku/index.html   Farebné sudoku
```

Každá ďalšia hra ide do vlastného priečinka (`<nazov>/index.html`) a pridá sa odkaz do `index.html`.

## GitHub Pages

https://ivann14.github.io/kids-games

## Inštalácia ako aplikácia (PWA)

Sudoku funguje aj offline a dá sa pridať na plochu:

- **iPad / iPhone:** otvor hru v Safari → Zdieľať → *Pridať na plochu*.
- **Android / Chrome:** menu → *Inštalovať aplikáciu*.

Po prvom otvorení s internetom ide hra aj bez pripojenia. Pri zmene ikon alebo manifestu zvýš `VERSION` v `sudoku/sw.js`.
