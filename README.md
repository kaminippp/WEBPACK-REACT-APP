# Created a react project without create-react-app command, used webpack for bundling and build purpose.

npm i react react-dom : Basic things required for react project

Webpack : compiled and bundle assets and code in a js file

webpack-dev-server : Gives a server and hot reloading facility both webpack and webpack-dev-server needs as a dev dependency so
npm i --save-dev webpack webpack-dev-server

also webpack-cli to allow us to use webpack commands like build app 
npm i --save-dev webpack-cli

babel needs as react uses es6, need to transpile down to brwoser friendly code, babel-core (core tranpliler)

babel-preset-react babel-preset-env(took place of babel-preset-2015 ,compiles es6 and also later version, checks what browser neesds and works accordingly, an intelligent tranpiler)

Needs loader (babel-loader) to understand jsx(react uses), html-webpack-plugin which creates build html file
npm i --save-dev babel-core babel-loader @babel/preset-react @babel/preset-env html-webpack-plugin

create a webpack.config.js and mention the entry, output, loader under module section, plugins under plugins section in opur case html-webpack-plugin woth template as index.html with id app which will be in use with react index.js if you want

create .babelrc to define your presets

create a react index.js file and write any code which you want to bunldled and build

Add scripts under scripts in package.json for starting the dev-server and building the app

![](https://github.com/kaminippp/WEBPACK-REACT-APP/blob/master/Screenshot.png)
