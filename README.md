## Semestrální úloha

Postupovala jsem prakticky stejně s kroky ve videích z praktických cvičení. Testy, které zabraňují v merge jsou taktéž udělané podle videí (v settings dané testy přes CircleCI, zde jsem zaškrtla však pouze build, protože jsem si nebyla jistá zda dávat i Deploy). Také jsem hledala v návodech jako CircleCI a stack overflow, nakonec když jsem nevěděla, tak jsem se zeptala kolegů na radu. Tímto jim chci poděkovat a dát kredit za to, že jsou ochotní a udělali si čas na mě mi vysvětlit, jak některé věci fungují.


## Installation Guide
- Install GIT - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- Install Docker - https://www.docker.com/products/docker-desktop

## Build/Run
- Source code of the React app is based on "react-shopping-cart" app made under MIT license by Jefferson Ribeiro

#### Requirements

- Node.js
- NPM

```javascript

/* First, Install the needed packages */
npm install

/* Then start both Node and React */
npm start

/* To run the tests */
npm run test

/* Build sources */
npm run build

/* Running e2e tests */
npm run wdio



```

## About tests .

- Unit tests
  - All components have at least a basic smoke test
- Integration tests
  - Fetch product and add to cart properly
- e2e
  - Webdriverio - Add and remove product from cart

### Copyright and license

The MIT License (MIT). Please see License File for more information.

Try to trigger
