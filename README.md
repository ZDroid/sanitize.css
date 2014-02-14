# Sanitize.css [![Build status](https://travis-ci.org/ZDroid/sanitize.css.png?branch=master)](https://travis-ci.org/ZDroid/sanitize.css) [![devDependency status](https://david-dm.org/ZDroid/sanitize.css/dev-status.png?theme=shields.io)](https://david-dm.org/ZDroid/sanitize.css#info=devDependencies)

> Minimal CSS normalization library

Based on the
[Normalize.css](https://github.com/necolas/normalize.css).

## Download

- [**ZIP**](https://github.com/ZDroid/sanitize.css/archive/master.zip)
- **Bower:** `bower install sanitize.css`

### CDN

- [cdnjs](http://cdnjs.com/libraries/sanitize.css/)
- [jsDelivr](http://www.jsdelivr.com/#!sanitize.css) (latest at
`//cdn.jsdelivr.net/sanitize.css/latest/sanitize.min.css`)

## Core changes

- Modules
- CSSComb support
- Improved comments
- Improved display definitions
- Consistent and modern element styles
- Improved vertical align of embedded content
- Responsive images

## Browser support

- **Chrome** and **Chromium**
- **Firefox**
- **Opera**
- **Safari** for OS X and iOS
- **Internet Explorer 9+**

## Compile

Wuzzle uses [Grunt](http://gruntjs.com) to compile Less code.

### Dependencies

You need [node.js](http://nodejs.org/download/) to use Grunt.

From the command line:

```bash
$ npm install -g grunt-cli
$ npm install # from the root Sanitize.css directory
```

When completed, you'll be able to run the various Grunt commands provided from
the command line.

### Commands

#### Default: `grunt [--modules="module..."]`

Compiles Less files.

`--modules` is space-separated list of modules. If `--modules` option is used,
it will just compile specified modules.

#### Watch: `grunt watch [--modules="module..."]`

Watches Less files and compiles them when they're changed.

## Modules

Modules are invidual files within `src/`.

- [**base**](https://github.com/ZDroid/sanitize.css/blob/master/src/base.less#files)
- [**display**](https://github.com/ZDroid/sanitize.css/blob/master/src/display.less#files)
- [**text**](https://github.com/ZDroid/sanitize.css/blob/master/src/text.less#files)
- [**embed**](https://github.com/ZDroid/sanitize.css/blob/master/src/embed.less#files)
- [**forms**](https://github.com/ZDroid/sanitize.css/blob/master/src/forms.less#files)
- [**tables**](https://github.com/ZDroid/sanitize.css/blob/master/src/tables.less#files)

## License

MIT &copy; [Zlatan Vasović](https://github.com/ZDroid)
