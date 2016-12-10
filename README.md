# React-Starter

This is my React starter project. Started from scratch, to learn the structure and all components involved.  
Based on the ["How to start a React project from scratch"] (http://andrewhfarmer.com/react-from-scratch/)


## Commands
**1. Git**
```
// initialize Git repo
git init
```

**2. NPM**
```
// create package.json
npm init -y

// create .gitignore and add node_modules to ignore list
node_modules

// install (afterwards) all dependencies via npm
npm install
```

**3. Babel**
```
// install Babel
npm install --save babel-core
npm install --save babel-preset-es2015
npm install --save babel-preset-react

// add .babelrc with the following
{
  "presets": ["es2015", "react"]
}
```

**4. Webpack**
```
// install Webpack
npm install --save webpack babel-loader
```
See the [tutorial step] (http://andrewhfarmer.com/build-your-own-starter/#4-webpack) for details.
