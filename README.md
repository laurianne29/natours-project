# Natours-project

## About

Here is my first one page create in Scss with some advanced Css properties.

## Requirements

* <strong>nodeJS</strong>, link here: <https://nodejs.org>
* <strong>package.json file</strong>: for that just write `npm init` on the terminal being sure to be into the project folder.
* <strong>node-sass package</strong>: write `npm install node-sass --save-dev`. The `--save-dev` is to be saved as a development dependency, it's like a tool for this project. If the package.json file is already in the folder, just write `npm install` which will install automatically the node-sass package.

### Compile
To compile our scss into css code: run the script compile:sass, for that just write `npm run compile:sass`.

### Reload
The command `live-server` will automatically reload the page on the browser each time you save your file.


## Architecture: The 7-1 Pattern

In this project the 7-1 pattern will be used in our sass folder to have a maintenable, scalable and well-organized project. As indicated by his name this architecture is composed by 7 folders and one main sass file to import all the files that are in these folders.

![7-1_pattern](https://user-images.githubusercontent.com/22610601/57609462-3b67f880-756f-11e9-8465-93ec0bdea63c.png)

As you can see we only have 5 folders in this architecture. Usually the 7-1 pattern also have a folder for <strong>themes</strong> in case if we have different themes and also a <strong>vendors</strong> folder which is for third party css like bootstrap css files, icon system or animation framework. I don't need these 2 folders for this project so we stick with these 5 folders.


<!--## Quick reminder of how to use Sass-->

<!-- ### Variables
Variables are like containers where we can store some data. Like the size of a font or the name of a color or any other values of css properties which will be reused more than once in our page.-->

<!-- ### Mixins -->

## Note

Actually some of the advanced css properties used to create complex css animations in this project are not supported by all browsers, spacially by IE 7, 8 or Edge maybe more. 
So, just take a look here <https://caniuse.com/> to know the compatibility with every browsers.

## License

This project is licensed under the MIT License - see the <a href="https://github.com/laurianne29/natours-project/blob/master/LICENSE">LICENSE</a> file for details.
