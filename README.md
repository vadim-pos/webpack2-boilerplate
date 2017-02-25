# Webpack2 boilerplate for new web project

## Contains
1. [Webpack 2.2](https://webpack.github.io)
2. [Babel](https://babeljs.io/)
3. [Pug](https://github.com/pugjs)
4. [SASS(SCSS)](http://sass-lang.com/)
5. [Karma](https://karma-runner.github.io/1.0/index.html)

## Setup
```
$ npm install
```

### Running in dev mode
```
$ npm start
```

### Build (production)
```
$ npm run build
```

## Notes
### Embedded resources in pug
Use require for all your embedded resources, to process them with webpack
```
div
  img(src=require("./my/image.png"))
```
