# Steps to create react app with webpack

 - Install react and react-dom <br> 
    npm install react react-dom
 - Create src folder and create a file - index.js inside the src folder

 - Install webpack, webpack-cli & webpack-dev-server, @babel/core, @babel/preset-env, @babel/preset-react, babel-loader as dev dependency
  
   npm i webpack webpack-cli webpack-dev-server @babel/core @babel/node @babel/preset-env @babel/preset-react babel-loader -D 

 - Create webpack.config.js with html plugin and babel loader
 - Copy the content from webpack config inside the project.

 - Command to build bundle js
   npx webpack --mode development
