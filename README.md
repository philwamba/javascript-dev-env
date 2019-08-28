# Package Development Environment
Reusable Javascript package development environment.

# Getting Started
### Package Management
This project was initalized using `npm` package manager.
### Bundling
### Minification
### Source maps
### Transpiling
### Dynamic HTML Generation
### Centralized HTTP
### Mock API Framework
### Linting
### Component Libraries
### Development Web server
### Automated testing
### Continuous Integration
### Automated Builds
### Automated Deployment
### Working example app
 
## Packages Explained (Installed Packages)
### What is Babel?
Babel is used to convert ES6+ code backwords to compatible versions.
Set up process involves running the following commands:
```bash
npm install --save-dev @babel/core @babel/cli @babel/preset-env
npm install --save @babel/polyfill
```
Creating a config file named `babel.config.js` in the root of your project with this content:
### Babel Loader
This is package that allows traspiling JavaScript files using Babel and Webpack.
```bash
npm install -D babel-loader @babel/core @babel/preset-env webpack
```

### Webpack 
A bundler for modules whose main purpose is to bundle JavaScript files for usage in a browser.
```bash
npm install webpack --save-dev
```

### CSS Loader
The css-loader interprets `@import` and `url()` like `import/require()` and will resolve them.

### ESLint
A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.
```bash
npm install eslint --save-dev
```
### eslint-plugin-import
This plugin intends to support linting of ES2015+ (ES6+) import/export syntax, and prevent issues with misspelling of file paths and import names.
```bash
npm install eslint-plugin-import --save-dev
```
### Eslint Watch
A simple command line tool that wraps Eslint and provides file watching and command line improvements to the currently existing project.
```bash
npm install eslint-watch --save-dev
```

## Other packages (Not Installed)

### Nodemon
A utility that will monitor for any changes in your source and automatically restart your server.
```bash
npm install nodemon --save-dev
```

## Quick Start
1.  Run `npm init -y` to initialize the project.

2. Add new dev dependencies
```json
"devDependencies": {
    "@babel/cli": "^7.5.5",
    "@babel/core": "^7.5.5",
    "@babel/preset-env": "^7.5.5",
    "babel-loader": "^8.0.6",
    "css-loader": "^3.2.0",
    "eslint": "^6.2.2",
    "webpack": "^4.34.0"
}
```