# Asset Pipeline

## What is it?
The asset pipeline provides a framework of concatenating and compressing your JavaScript and CSS assets. Instead of loading all of your JS and CSS files, only one JS and one CSS file are loaded.

## How is it included?
Via sprockets-rails gem

You can manually disable it upon rails app creation by executing the following on the command line:

rails new appname --skip-sprockets

## Key Features

### Concatenation
Reduces the number of assets loaded by combining all JS files into one JS file and all CSS files into one CSS file.

This single file is called the 'manifest file'. Represented as application.js or application.css

### Compression
Removes whitespace and comments from CSS files.

"Uglifies" JavaScript (reduces unnecessary whitespace and performs other optimizations)

### Pre-compilation of higher level languages
Sass -> CSS
CoffeeScript -> JavaScript

## Example
http://secret-shore-70824.herokuapp.com/


