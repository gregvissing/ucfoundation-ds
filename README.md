# Building A Design System With CSS

This is your **main project** for this workshop! Let’s take a look around 👇

The main project consists of the following tech:

- [Sass](https://sass-lang.com/)
- [Fractal](http://fractal.build/)
- [HTML (Nunjucks)](https://mozilla.github.io/nunjucks/)

All of the HTML has been pre-written for you (minus some utility classes etc.) and the project structure for [Sass](https://sass-lang.com/) and [Gorko](https://github.com/hankchizljaw/gorko) is also set up.

## Getting started

Unzip the project files and using your terminal, run the following **inside the project folder**:

```bash
npm install
```

There are two commands that you can run:

1. `npm start`: this will serve up a local copy of your pattern library and watch for any changes
2. `npm run build`: this will build all the patterns for you and put them in `dist`

## Project structure

### Patterns

All of the patterns that live in the [Fractal pattern library](http://fractal.build/) have HTML pre-written, but you’ll probably want to manage them yourself too.

The following folders contain patterns:

1. `01-design-tokens`
2. `02-utilities`
3. `03-blocks`
4. `04-compositions`
5. `05-prototypes`

Each pattern contains at least a HTML file, but might also contain a `config.json` file. This file contains [context](https://fractal.build/guide/core-concepts/context-data.html#context-data) which is available to the templates.

### CSS

We’re using [Sass](https://sass-lang.com/) and [Gorko](https://github.com/hankchizljaw/gorko) to write our CSS and all the files can be found in the `src/scss` folder. It’s all organised as per the [CUBE CSS methodology](//cube.fyi).

### JS

You’ll be happy to know we’re not writing any JS in this workshop!
