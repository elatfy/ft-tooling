# ft-tooling

**Features**

- Concatenate, minify,transpile JavaScript.
- Compile, minify, autoprefix Sass.
- Copy static files and folders into your `dist` directory.
- Watch for file changes, and automatically recompile build and reload webpages.

## Getting Started

### Dependencies

Make sure these are installed first.

- [Node.js](http://nodejs.org)
- [Gulp Command Line Utility](http://gulpjs.com) `npm install --global gulp-cli`

### Quick Start

1. In bash/terminal/command line, `cd` into your project directory.
2. Run `npm install` to install required files and dependencies.
3. When it's done installing, run the task runner command to get going:
   - `gulp` automatically compiles files and applies changes using [BrowserSync](https://browsersync.io/) when you make changes to your source files.

## Documentation

Add your source files to the appropriate `app/src` subdirectories. Gulp will process and and compile them into `dist`.

- JavaScript files in the `app/src/js` directory will be compiled to `dist/js`. Files in subdirectories under the `js` folder will be concatenated. For example, files in `js/detects` will compile into `detects.js`.
- Files in the `app/src/sass` directory will be compiled to `dist/css`.

### package.json

The `package.json` file holds all of the details and packages dependencies about your project.

## Options & Settings

Gulp Task runnner makes it easy to customize projects you can easily delete or modify tasks.

Options and settings are located at `gulpfile.js`.
