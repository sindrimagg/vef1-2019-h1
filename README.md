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
 - sim42@hi.is
 - [sindrimagg](https://github.com/sindrimagg)

### Ægir Örn Kristjánsson
 - aok10@hi.is
 - [aegirok](https://github.com/aegirok)
 ---
## Að keyra verkefnið
Verkefnið er skrifað í SASS og HTML, notast er við [node.js](https://nodejs.org/en/) með pökkum [node-sass](https://www.npmjs.com/package/node-sass) (til að þýða .scss skrár í .css) og [browser-sync](https://www.npmjs.com/package/browser-sync).
Til að keyra forritið þarf að skrifa í rót verkefnis
```bash
npm install
npm run sass
npm run browser-sync
```

Eftir að pökkum hefur verið hlaðið inn á tölvuna er hægt að athuga hvort SASS skrár fylgi viðmiðunarreglum með [stylelint](https://stylelint.io/).
Til að athuga hvort SASS skrár fylgi viðmiðunarreglum þarf að skrifa í rót verkefnis
```bash
npm run lint
```
---
## Útskýring
Allar síður fyrir utan forsíðu eru geymdar í pages möppu. Sass skrár geymdar í scss möppu. [Config.scss](scss/config.scss) inniheldur grunnskilyrði líkt og litapallettu, mixin fyrir grid og leturgerðarfjölskyldur. Sérstakar SASS skrár eru fyrir header, footer og hverja síðu fyrir sig (athuga að SASS skráin fyrir staff.html heitir [flipcards.scss](scss/flipcards.scss). 

Það er sérstök skrá, [button.scss](scss/button.scss), fyrir takkana sem innihalda cart icon. Aðrir takkar hafa klasann grid__link sem tekinn er frá [forsida.scss](scss/forsida.scss).
Formið í cart endurnýtir að mestu kóða úr [products.html](pages/products.html) og [products.scss](scss/products.scss).


