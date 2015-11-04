# Gulp, Nunjucks, SASS

A nice little Gulp project using [Nunjucks](http://mozilla.github.io/nunjucks/),[SASS](http://sass-lang.com/) and [Gulp](http://gulpjs.com/). Browsersync runs out of 'dist' folder and watches all Nunjucks templates, SASS and JS and live reloads in browser on change. Also worked in some img min and moving fonts and assets to a 'dist' folder for easy deployment.


Gulp tasks used:

- sass
- autoprefixer
- sassdoc
- browserSync
- nunjucksRender
- script concat
- imagemin
- pngquant


## Setup

1) Install [Gulp](http://gulpjs.com/) and [NPM](http://nodejs.org) if you do not already have them.

2) Install npm dependencies
```
npm install
```

3) Run Gulp
```
gulp
```

