# Fountain React Generator

[![React](docs/assets/react.png)](https://facebook.github.io/react/)

> This Yeoman generator allows you to start an Angular1 web app with the best Developer Experience out of the box!

> No matter what framework or module management you want to use, we got you covered with a cutting edge working configuration.

> We use [Gulp 4](http://gulpjs.com/) as a task manager but we'll ask you questions about:
- Modules management: Webpack, SystemJS, none
- JS preprocessor: Babel, TypeScript, none
- CSS preprocessor: Sass, Less, none

This generator is a sub-generator of the the Yeoman Fountain generator for webapps [generator-fountain-webapp](https://github.com/FountainJS/generator-fountain-webapp).

## Generator Fountain React structure

To take profit of the best of the Yeoman infrastructure, we heavily relies on the composability natures of the generators.

Thereby, each needs of your future application will be addressed by a dedicated Yeoman generator (each will be used depending of the options you selected or not).

More informations in [DESIGN.md](http://fountainjs.io/doc/design).


### Web tooling layer
[![Gulp](docs/assets/gulp.png)](https://github.com/FountainJS/generator-fountain-gulp)
[![ESLint](docs/assets/eslint.png)](https://github.com/FountainJS/generator-fountain-eslint)
[![BrowserSync](docs/assets/browsersync.png)](https://github.com/FountainJS/generator-fountain-browsersync)
[![Karma](docs/assets/karma.png)](https://github.com/FountainJS/generator-fountain-karma)

### Module management layer
[![Webpack](docs/assets/webpack.png)](https://github.com/FountainJS/generator-fountain-webpack)
[![SystemJS](docs/assets/systemjs.png)](https://github.com/FountainJS/generator-fountain-systemjs)
[![Bower](docs/assets/bower.png)](https://github.com/FountainJS/generator-fountain-inject)


## Usage

### Requirement Node 4+ && NPM 3+
This generator is targeted to be used with Node >= 4.0.0 and NPM => 3.0.0. You can check your version number with the command
```
node --version && npm --version
```

### Install

##### Install required tools `yo`:
```
npm install -g yo
```

##### Install `generator-fountain-react`:
```
npm install -g generator-fountain-react
```


### Run

##### Create a new directory, and go into:
```
mkdir my-new-project && cd my-new-project
```

##### Run `yo fountain-react`, and select desired technologies:
```
yo fountain-react
```

### [Start development](http://fountainjs.io/doc/usage/#use-npm-scripts)


## [Changelog](https://github.com/FountainJS/generator-fountain-react/releases)


## [Contributing](http://fountainjs.io/doc/contributing)
