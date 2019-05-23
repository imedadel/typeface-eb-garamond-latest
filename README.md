
# Typeface EB Garamond Latest

The CSS and web font files to easily self-host [EB Garamond](http://www.georgduffner.at/ebgaramond/). This package is inspired by the effort of Kyle Mathews to create [npm packages for all typefaces](https://www.bricolage.io/typefaces-easiest-way-to-self-host-fonts/) to improve font loading performance.

## Install

```
npm install --save typeface-eb-garamond-latest
```

## Usage

This package assumes you’re using webpack to process CSS and font files. Each typeface package includes all font files for modern browsers (WOFF2 and WOFF) and a CSS file with font-face declarations pointing at these files.

You will need to have webpack or a different bundler setup to load css and font files. Many tools built with Webpack will work out of the box with Typefaces such as [Create React App](https://github.com/facebookincubator/create-react-app) and [Gatsby](https://github.com/gatsbyjs/gatsby).

Simply require the package in your project’s entry file:

```javascript
// Load the Public Sans typeface
import 'typeface-eb-garamond-latest';
```