# Natours Project

This is Huy's Natours Project, a pseudo nature touring one-page site, for Jonas Schmedtmann's Advanced CSS and SASS course. 

It demonstrates the usage of:

* SASS / SCSS (mixins, variables, etc.)
* Advanced CSS3 techniques (animations, custom responsive grid, background videos, media queries, etc.)
* The checkbox hack for triggering a navigation
* The anchor link hack for triggering popups
* 7-1 SASS directory pattern
* BEM (block-element-modifier) CSS naming conventions
* Building SASS/CSS through compiling SCSS files, concatenating multiple CSS files, prefixing CSS files for browser support of the latest 10 versions, and finally minifying the CSS file.

# Starting the project
To install dependencies and start the project with a server listening on port 8080, execute the following:

```sh
npm install 
npm start
```

# Developing the project
To install dependencies and develop on the project with live-reload and auto-compiling of the 7-1 SASS directories, execute the following:

```sh
npm install
npm start
```

## Building the latest minified CSS
To build the minified CSS for optimized deployment, execute the following:

```sh
npm run build:css
```

## Important
Uncomment the developmental CSS includes and uncomment the minified CSS include on index.html when developing. Do the inverse when deploying.