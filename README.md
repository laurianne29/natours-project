# natours-project

## About

Here is my first one page create in Scss with some advanced Css properties.

## Requirements

* <strong>nodeJS</strong>, link here: <https://nodejs.org>
* <strong>package.json file</strong>: for that just write `npm init` on the terminal being sure to be into the project folder.
* <strong>node-sass package</strong>: write `npm install node-sass --save-dev`. The `--save-dev` is to be saved as a development dependency, it's like a tool for this project. If the package.json file is already in the folder, just write `npm install` which will install automatically the node-sass package.

### To compile
To compile our scss into css code: run the script compile:sass, for that just write `npm run compile:sass`.

### To reload
The command `live-server` will automatically reload the page on the browser each time you save your file.


## Quick reminder of how to use Sass

### Variables
Variables are like containers where we can store some data. Like the size of a font or the name of a color or any other values of css properties which will be reused more than once in our page.

### Mixins


## Note

Actually some of the advanced css properties used to create complex css animations in this project are not supported by all browsers, spacially by IE 7, 8 or Edge maybe more. 
So, just take a look here <https://caniuse.com/> to know the compatibility with every browsers.
