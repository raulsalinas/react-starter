# React-Starter

A empty project.

## Building and running on localhost

First install dependencies:

```sh
npm install
```

To run in hot module reloading mode:

```sh
npm start
```

To create a production build:

```sh
npm run build-prod
```

To create a development build:

```sh
npm run build-dev
```

## Running

Open the file `dist/index.html` in your browser

## How to create your project yourself
### Create an NPM project and install dependencies
```
mkdir myapp
cd myapp
npm init -y
npm install --save-dev webpack webpack-cli @babel/preset-react babel-loader @babel/core @babel/preset-env @hot-loader/react-dom webpack-dev-server css-loader style-loader sass-loader node-sass postcss-loader autoprefixer file-loader url-loader
npm install react react-dom react-hot-loader moment
```
### Create webpack.config.js in the root and copy the contents of the generated file

### Create .babelrc in the root and copy the contents of the generated file

### Create folders src and dist and create source code files


