# officialBootWebpack
The repo with prepared Bootstrap and Webpack for easy build. 

### This is :
### Bootstrap and Webpack
### The official guide for how to include and bundle Bootstrap’s CSS and JavaScript in your project using Webpack.

### https://github.com/twbs/bootstrap/blob/v5.3.0-alpha2/site/content/docs/5.3/getting-started/webpack.md


npm init -y
npm i --save-dev webpack webpack-cli webpack-dev-server html-webpack-plugin
npm i --save bootstrap @popperjs/core
npm i --save-dev autoprefixer css-loader postcss-loader sass sass-loader style-loader

mkdir {src,src/js,src/scss}
touch src/index.html src/js/main.js src/scss/styles.scss webpack.config.js

### fill out index.html, webpack.config.js, package.js 

### npm start - start server

### npm run watch - watch changes
