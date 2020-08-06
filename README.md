# [React][react-url] dla początkujących - Poradnik 


## [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/master/LICENSE) [![npm version](https://img.shields.io/npm/v/react.svg?style=flat)](https://www.npmjs.com/package/react) 


<!-- <h3 align="center"> <a href="https://pl.reactjs.org">React</a></h3> -->
<p align="center">
  <a href="https://pl.reactjs.org">
    <img alt="react" width="104px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" alt="React logo">
  </a>
</p>

Github: [facebook/react](https://github.com/facebook/react) <br/>
Dokumentacja React dostępna na [stronie projektu](https://reactjs.org/docs)

### A: Co potrzebujemy?

#### 1. node.js

Możemy zainstalowac ze strony [nodejs.org][nodejs-url] pobierając plik .pkg
lub wykorzystując *Homebrew* 

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Sama instalacja **node.js** odbywa się z wykorzystaniem komendy:

```zsh
brew install node
```

Sprawdzic aktualnie zainstalą wersję nodejs można przy pomocy komendy

```zsh
node -v
```

Pod [tym linkiem](https://changelog.com/posts/install-node-js-with-homebrew-on-os-x) znajduje się bardziej szczegółowy poradnik intalacji node.js wykorzystując **brew**

#### 2. npm 
[npm][npmjs-url] to  menadżer pakietów dla JavaScript, zostanie zainstalowany automatycznie podczas instalacji node.js
 
#### 3. yarn
[Yarn][yarn-url] to kolejny menadżer pakietów dla JavaScript - więcej o zaletach tego narzędzia można przeczytac na [tej stronie](https://www.nafrontendzie.pl/czym-jest-yarn-czego-sluzy)

```zsh
brew install yarn
```

aktualnie zainstalowaną wersję sprawdzimy komendą:
```zsh
yarn -v
```

##### Lista komend yarn

`yarn start` - uruchamia serwer

`yarn build` - przygotowuje pliki na produkcję

`yarn test` -  Starts the test runner.

`yarn eject` - czyści i usuwa

#### 4. React developer tools
Przyda się też rozszerzenie do przeglądarki chrome - [react deveoper tools][rdt-url]
 
## B: Create React App
Strona [projektu][create-react-url]
'Set up a modern web app by running one command.'
 
```
npx create-react-app my-app
cd my-app
npm start <albo> yarn start
```

trochę więcej o *npx* -> [link](https://blog.npmjs.org/post/162869356040/introducing-npx-an-npm-package-runner) ... [stockoverflow](https://stackoverflow.com/questions/50605219/difference-between-npx-and-npm)

```
NPM - Manages packages but doesn't make life easy executing any.
NPX - A tool for executing Node packages.
```

Zajmie to chwile po czym w oknie terminalu ukaże nam się lista przydatnych komend z krótkim opisem

![preview][c-r-a-url]

Więcej szczegółów zostanie zawarte w wygenerowanym właśnie pliku `README.md`

## Wykorzystane frameworki
### CSS
* [tailwind](https://tailwindcss.com)
  
```
yarn add tailwindcss
```

<!-- Poradnik bazuje na repozytorium [QuentinWatt](https://github.com/QuentinWatt) <br/>
oraz jego tutorialu (React JS for beginners) [YouTube](https://www.youtube.com/watch?v=HDEVMozZhv8&list=PL41lfR-6DnOoTiHU4Ub6efP-p3xAq3eiV). -->


<!-- Linki -->
[nodejs-url]: https://nodejs.org/en/
[npmjs-url]: https://www.npmjs.com
[yarn-url]: https://yarnpkg.com
[rdt-url]: https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi
[react-url]: https://pl.reactjs.org/
[create-react-url]: https://create-react-app.dev

[c-r-a-url]: https://raw.githubusercontent.com/pajlotapps/React-dla-poczatkujacych-poradnik/master/cra.png?raw=true
