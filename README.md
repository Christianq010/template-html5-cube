# Template Starter Pack
A light package for compiling Sass and running a dev server and managing bower dependencies from free HTML5 on the web.

## Usage
> This project is a basic template for turning HTML5 templates on the web into projects I can edit with SASS and js dependencies handled via bower.

> Also contains a few points on bower and npm as a refresher for me when initilizing a Front End project.


### Version
1.0.0

## Installation

### NPM
* To start a package.json use `npm init`
* Install packages by using `npm install gulp-sass gulp browersync` etc.
* Install the dependencies after cloning this project (gulp, gulp-sass, browser-sync)

```sh
$ npm install
```

### Bower
* Initialize bower with `bower init`
* Install a bower package and update `.json` with `bower install bootstrap -S`
* Install any github url with `bower install url`
* [Bower installer] (https://github.com/rquadling/bower-installer) provides an easy way for the main files to be installed or moved to one or more locations. Simply add to your `bower.json` an install key and path attribute:

```
{
    "name": "test",
    "version": "0.1",
    "dependencies": {
        "backbone": "latest"
    },
    "install": {
        "path": "some/path",
        "sources": {
            "requirejs": "bower_components/requirejs/require.js"
        }
    }
}
```

### Run Server
This will watch your sass files, compile them and run your dev server at http://localhost:3000

```sh
$ npm start
```

### Dependencies on this project
Directories and files copied from template.

* Bootstrap
* [Animate.css](https://github.com/daneden/animate.css)
* Icomoon free - [repo](https://github.com/layerssss/icomoon-bower)
* [Magnific Popup](https://github.com/dimsemenov/Magnific-Popup)
* Owl.carousel - [repo](https://owlcarousel2.github.io/OwlCarousel2/docs/started-welcome.html)
* jQuery Easing - [1.3 repo](https://github.com/jozefizso/bower-jquery-easing)
