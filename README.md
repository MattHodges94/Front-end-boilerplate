# Front End Boilerplate - Gulp, Babel, SASS, Browsersync

## To Start

* Ensure Node, NPM, and gulp are installed globally.
* Run 'npm i'

## Build

Generate a fresh build of your project. Task will run several individual tasks on files within `./src` and then output them to `./build`.

Run: `gulp build`

## Server

Start a local dev server. Gulp will watch for any changes to files and reload browser while server is running.

Run: `gulp server`

Access dev server at - http://localhost:3000

## Assets

Run several individual tasks to copy static files from `./src` to `./build`.

Run: `gulp assets`

### Data

Copy data files to `./build/data`.

Run: `gulp data`

### Fonts

Copy font files to `./build/fonts`.

Run: `gulp fonts`

### Images

Remember to optimise!

Run: `gulp images`

### Media

Copy media files to `./build/media`.

Run: `gulp media`

### Miscellaneous

Copy miscellaneous files, such as `.htaccess` or `robots.txt`, to the root of `./build`. If your project require custom settings per environment, then you can save individual files into appropriate directory within `./src/misc`.

Run: `gulp misc`

### Vendors

Bundle vendor files to `./build/vendors`. 

Run: `gulp vendors`

## Scripts

Run a series of sub-tasks to generate final JavaScript files. 

*Note: Each file on the root of `./src/scripts` will be compiled to its own file in `./build/scripts`. Each file can have own includes, just like Sass with `@import` functionality.*

Run: `gulp scripts`

## Styles

Run a series of sub-tasks to generate final CSS files.

*Note: Each file on the root of `./src/styles` will be compiled to its own file in `./build/styles`.*

Run: `gulp styles`

## Views

Run a series of sub-tasks to generate final HTML files.

Run: `gulp views`


