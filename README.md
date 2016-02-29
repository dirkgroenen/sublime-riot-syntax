# Riot Syntax

> Only supports **Sublime Text 3**.

Language definitions for [ES6+ JavaScript](http://kangax.github.io/compat-table/es6/) with [RiotJS](http://riotjs.com) extensions for Sublime Text 3.

Adds syntax highlighting support for HTML right inside of ES6 strings (i.e \`...\`) when it's inside of `riot.tag('your-tag', ...)`.

This package is a port of [Babel-Sublime](https://github.com/babel/babel-sublime) for RiotJS. The Babel-Sublime only supports syntax highlighting of [React](https://github.com/facebook/react) `.jsx` components. This package is here to change it. Basically, all it does, is that it makes your HTML inside of \`...\` strings to act like it's React's HTML inside of JavaScript.

Please note, that it has no `jsx` support. It ships with a new syntax called `JavaScript Riot` which should be used only for your Riot's pure-js tags. If you are not planning to ever use `jsx`, you can use it as your default JavaScript syntax.

## Screenshots

<img src="https://raw.githubusercontent.com/ilearnio/sublime-riot-syntax/master/screenshots/before-after.png" width="587" height="396">

## Why to use plain JavaScript instead of `.tag` files?
  1. Linter support
  2. You can use JS sourcemaps
  3. Easier debugging (browser or terminal)
  4. Easier testing
  5. No extra compilation step
  6. Require tags with Webpack or Browserify directly, without any loaders

## Installation

Find it as [**Riot Syntax**](https://packagecontrol.io/packages/riot-syntax) through [Package Control](https://packagecontrol.io/).

#### Setting as the default syntax

To set it as the default syntax for a particular extension:
  1. Open a file with that extension,
  2. Select `View` from the menu,
  3. Then `Syntax` `->` `Open all with current extension as...` `->` `JavaScript Riot`.
  4. Repeat this for each extension (e.g.: `.js`, `.jsr`, `.riot`).

#### Setting a Color Scheme

Riot Syntax comes bundled with `Next`, `Monokai` and `Github` color themes. Select one from `Preferences` `->` `Color Scheme` `->` `Riot Syntax`

* Riot Syntax supports modern JavaScript syntax, including [arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions), [destructuring](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment), [shorthand methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Method_definitions), [template strings](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/template_strings), and more.
