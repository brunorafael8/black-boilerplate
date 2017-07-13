<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/3603793/14390922/a999424c-fd8f-11e5-8fbb-ab908a1d4740.png" width="200">
</p>

# Bruno Rafael

[![license](https://img.shields.io/github/license/LFeh/black-boilerplate.svg)](./license.md)
[![GitHub contributors](https://img.shields.io/github/contributors/LFeh/black-boilerplate.svg)](https://github.com/LFeh/black-boilerplate/graphs/contributors)

This project uses Pug, Stylus, Gulp and Browsersync.

Maybe you want to read about them:
- [NPM Scripts](https://docs.npmjs.com/misc/scripts)
- [GulpJS](http://gulpjs.com/)
- [Pug](https://github.com/pugjs/pug)
- [Stylus](http://learnboost.github.io/stylus/)
- [Browsersync](https://www.browsersync.io/)

For grid system uses [Lost](https://github.com/peterramsing/lost) with some help from [Rucksack](http://simplaio.github.io/rucksack/) for animations, reset and a lot of great mixins, [Rupture](https://github.com/jenius/rupture) for responsive utilities. And [Font Magician](https://github.com/jonathantneal/postcss-font-magician/) to get the webfonts.


## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)
- [GulpJS](http://gulpjs.com/)


```sh
# Clone this repository
$ git clone git@github.com:LFeh/black-boilerplate.git
$ cd black-boilerplate

# install gulp globally
$ npm install -g gulp

# install dependencies
$ npm run setup

```

With the commands above, you have everything to start.

### Folders and Files

```sh
├── README.md
├── dist
│   ├── css/
│   ├── img/
│   ├── svg/
│   ├── icons/
│   ├── js/
│   ├── styleguide/
│   ├── index.html
├── gulpfile.js
├── package.json
└── src
    ├── img/
    ├── svg/
│   ├── icons/
    ├── js/
    ├── styl
    │   ├── _core/*.sass
    │   ├── vendors/*.sass
    │   ├── quarks/*.sass
    │   ├── atoms/*.sass
    │   ├── molecules/*.sass
    │   ├── organisms/*.sass
    │   ├── pages/*.sass
    │   └── style.sass
    └── pug
        └── index.pug
```

Those folders and file will change during the project.

### Code Standards

This project uses my own [Coding Style](https://github.com/LFeh/coding-style) as code reference.

This project also uses [Husky](https://github.com/typicode/husky) to prevent commit and push messy and wrong code.

To help you, this project has a `npm run fix` command to fix all eslint errors.


#### Parker CSS

To view a reporter of CSS files, use a `npm run reporter` command.


### Tasks
 
- `npm start`: run all tasks and initialize watch for changes and a server
- `npm test`: lint javascript and css 
- `npm run setup`: install all dependencies
- `npm run fix`: command to fix all eslint errors
- `npm run reporter`: test css complexity
- `npm run dist`: run all tasks to dist
- `npm run html`: compile html files
- `npm run js`: compile js files
- `npm run css`: compile css files
- `npm run images`: compress imaages files
- `npm run svg`: compress svg files
- `npom run icons`: generate sprite of icons 

## Credits

This boilerplate uses as a base the awesome [Qualy Boilerplate](https://github.com/Qualy-org/qualy) by [@Willian_justen](https://twitter.com/Willian_justen) :heart:


## License

[MIT License](http://felipefialho.mit-license.org/) © Felipe Fialho
