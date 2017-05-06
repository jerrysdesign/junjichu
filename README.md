# 國立臺灣歷史博物館|軍機處錄副奏折微卷數位資料庫

*By JJ Hung*

## Gulp

Gulp will watch for file changes to the following files:

* *.pug
* *.scss
* *.js
* *.img

When any of these Gulp will compile / copy over those changes from the `src/` to the `dist/` directory and refresh the web browser.

## Pug

In the `src/` are Pug `*.pug` files. These are the source HTML files and watched by  Gulp to compile to the `dist/*.html` directory.

### Extends

In the `src/extends` are Pug extend file locate. These are used as master layout files that the `index.pug` uses.

### Includes

Pug can use include files as well to have content created once and re-used.