# Steps to create react app with webpack

 - Install react and react-dom
    npm install react react-dom
 - Create src folder and file index.js inside the folder

 - Install webpack, webpack-cli & webpack-dev-server, @babel/core, @babel/preset-env, @babel/preset-react, babel-loader as dev dependency
  npm i webpack webpack-cli webpack-dev-server -D
 npm i @babel/core @babel/node @babel/preset-env @babel/preset-react babel-loader -D 

create webpack.config.js with html plugin and babel loader
copy the content from webpack config inside the project and paste it

Command to build bundle js
npx webpack --mode development
