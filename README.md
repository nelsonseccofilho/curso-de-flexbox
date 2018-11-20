# Mini-curso de Flexobx | Material de apoio

Neste mini-curso você trabalhará com o flexbox da mesma forma que trabalharia no seu dia a dia, npm, scss e todas as explicações detalhadas nos comentários.

### Dependências
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

https://nodejs.org/en/download/

https://yarnpkg.com/en/docs/install

### Instalação

```
npm install ou yarn install
```

### Start Dev Server

```
npm run start ou yarn start
```

### Build Prod Version

```
npm run build ou yarn build
```

### Features:

* Suporte ES6 via [babel] (https://babeljs.io/) (v7)
* Suporte SASS via [sass-loader] (https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader] (https://github.com/MoOx/eslint-loader)

Quando você executa `npm run build` usamos o [mini-css-extract-plugin] (https://github.com/webpack-contrib/mini-css-extract-plugin) para mover o css para um arquivo separado. O arquivo css é incluído na cabeça do `index.html`.
