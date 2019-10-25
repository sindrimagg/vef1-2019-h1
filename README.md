# Hópverkefni 1
---
## TODO

- Gera README
- laga button í námskeið
- laga lint
---
## Aðilar í hóp

### Jón Gunnar Hannesson
 - jgh12@hi.is
 - [jugguhu](https://github.com/jugguhu)

### Sindri Magnússon

 - [sindrimagg](https://github.com/sindrimagg)

### Ægir Örn Kristjánsson
 - aok10@hi.is
 - [aegirok](https://github.com/aegirok)
 ---
## Að keyra verkefnið
Verkefnið er skrifað í sass, notast er við [node.js](https://nodejs.org/en/) með pökkum [node-sass](https://www.npmjs.com/package/node-sass) (til að þýða .scss skrár í .css) og [browser-sync](https://www.npmjs.com/package/browser-sync).
Til að keyra forritið þarf að skrifa í rót verkefnis
```bash
npm install
npm run sass
npm run browser-sync
```

Eftir að pökkum hefur verið hlaðið inn á tölvuna er hægt að athuga hvort sass skrár fylgi viðmiðunarreglum með [stylelint](https://stylelint.io/).
Til að athuga hvort sass skrár fylgi viðmiðunarreglum þarf að skrifa í rót verkefnis
```bash
npm run lint
```
---
## Útskýring

