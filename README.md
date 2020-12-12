# package.json

{
    "name": "app-shell",
    "version": "0.2.0",
    "private": true,
    "license": "Apache Version 2.0",
    "engines": {
      "node": ">=4.1.0"
    },
    "scripts": {
      "start": "node app.js",
      "monitor": "gulp dev",
      "postinstall": "gulp",
      "deploy": "gcloud preview app deploy app.yaml --promote"
    },
    "main": "app.js",
    "dependencies": {
      "babel-preset-es2015": "^6.0.15",
      "babelify": "^10.0.0",
      "browserify": "^17.0.0",
      "del": "^6.0.0",
      "express": "^4.17.1",
      "express-handlebars": "^5.2.0",
      "gcloud": "^0.37.2",
      "glob": "^7.1.6",
      "gulp": "^4.0.2",
      "gulp-autoprefixer": "^7.0.1",
      "gulp-bump": "^3.2.0",
      "gulp-env": "^0.4.0",
      "gulp-eslint": "^6.0.0",
      "gulp-if": "^3.0.0",
      "gulp-imagemin": "^7.1.0",
      "gulp-license": "^1.1.0",
      "gulp-minify-css": "^1.2.1",
      "gulp-minify-html": "^1.0.6",
      "gulp-nodemon": "^2.5.0",
      "gulp-rename": "^2.0.0",
      "gulp-replace": "^1.0.0",
      "gulp-sass": "^4.1.0",
      "gulp-sourcemaps": "^3.0.0",
      "gulp-streamify": "^1.0.2",
      "gulp-uglify": "^3.0.2",
      "gulp-util": "^3.0.6",
      "require-dir": "^1.2.0",
      "run-sequence": "^2.2.1",
      "sw-precache": "^2.2.0",
      "vinyl-source-stream": "^2.0.0"
    }
  }
