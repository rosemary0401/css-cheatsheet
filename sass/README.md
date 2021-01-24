# What
* Sass is a CSS pre-processor
* Sass files are processed, and turned into regular CSS style sheets 
* It does not extend the CSS standard
* A browser does not understand Sass code

# There are two syntaxes available for Sass
* Sass (old syntax)
  * Syntax is similar to Ruby
* SCSS 
  * Syntax is similar to CSS
  * every regular valid CSS3 is also valid SCSS
  * It is an extension of the syntax of CSS

# Installation
https://sass-lang.com/install
```
npm install -g sass
```

# How to run
```
sass hello.scss hello.css
```

A .css.map file will be created. It is a JSON format file that links the CSS file to its source files, normally, files written in preprocessors (i.e., Less, Sass, Stylus, etc.), this is in order do a live debug to the source files from the web browser




