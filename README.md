#Package Development Environment
Reusable Javascript package development environment.
## Package Management
Project initalized with `npm` package manager.
## Bundling
## Minification
## Source maps
## Transpiling
## Dynamic HTML Generation
## Centralized HTTP
## Mock API Framework
## Linting
## Component Libraries
## Development Web server
## Automated testing
## Continuous Integration
## Automated Builds
## Automated Deployment
## Working example app

## Step by Step

1.  Run `npm init -y` to initialize the project.

2. Add new dev dependencies
```
"devDependencies": {

}
```
### What is Babel?
Babel is used to convert ES6 code backwords to compatible versions.
Set up process involves running the following commands:
```
npm install --save-dev @babel/core @babel/cli @babel/preset-env
npm install --save @babel/polyfill
```
Creating a config file named `babel.config.js` in the root of your project with this content:
### What is included
### Babel Loader
This is package that allows traspiling JavaScript files using Babel and Webpack.

```npm install -D babel-loader @babel/core @babel/preset-env webpack```