# Webpack4-init


step 1: npm init -y

step 2: npm install webpack webpack-cli --save-dev

step 3: npx webpack

step 4: npx webpack --config webpack.config.js

step 5: npm run build

step 6: npm install --save-dev html-webpack-plugin

step7: npm install --save-dev clean-webpack-plugin

#Webpack4-Development


set- devtool: 'inline-source-map' in webpack.config.js

install --save-dev webpack-dev-server

Change in config file to tell web server where to start

devServer: {

     contentBase: './dist'
     
   },
   
Run server webpack-dev-server --open; it should be http://localhost:8080/

Add a script to easily run the dev server as well, package.json

"start": "webpack-dev-server --open",





