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

## Step by Step Guide 
## Packages Explained (Installed Packages)
### What is Babel?
Babel is used to convert ES6 code backwords to compatible versions.
Set up process involves running the following commands:
```
npm install --save-dev @babel/core @babel/cli @babel/preset-env
npm install --save @babel/polyfill
```
Creating a config file named `babel.config.js` in the root of your project with this content:

### Babel Loader
This is package that allows traspiling JavaScript files using Babel and Webpack.
```npm install -D babel-loader @babel/core @babel/preset-env webpack```

### Webpack 
A bundler for modules whose main purpose is to bundle JavaScript files for usage in a browser.
```npm install webpack --save-dev```

### CSS Loader
The css-loader interprets `@import` and `url()` like `import/require()` and will resolve them.

### ESLint
A tool for identifying and reporting on patterns found in ECMAScript/JavaScript code, with the goal of making code more consistent and avoiding bugs.
```npm install eslint --save-dev```

## Other packages (Not Installed)

### Nodemon
A utility that will monitor for any changes in your source and automatically restart your server.
```npm install nodemon --save-dev```

## Quick Start
1.  Run `npm init -y` to initialize the project.

2. Add new dev dependencies
```
"devDependencies": {

}
```