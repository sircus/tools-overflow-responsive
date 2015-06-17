# sircus-tools-overflow-responsive

[![npm version](https://img.shields.io/npm/v/sircus-tools-overflow-responsive.svg?style=flat)](https://www.npmjs.com/package/sircus-tools-overflow-responsive)

> A responsive overflow tools Module of Sircus.

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-tools-overflow-responsive sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-tools-overflow-responsive";
/*
@import "sircus-tools-overflow-responsive/lib/sm";
@import "sircus-tools-overflow-responsive/lib/md";
@import "sircus-tools-overflow-responsive/lib/lg";
*/
@import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-global-property/converted";
@import "./node_modules/sircus-tools-overflow-responsive/converted";
// @import "./node_modules/sircus-tools-overflow-responsive/scss/sm";
// @import "./node_modules/sircus-tools-overflow-responsive/scss/md";
// @import "./node_modules/sircus-tools-overflow-responsive/scss/lg";
```


> html

```html
<div class="t-sm-overflow"></div>
<div class="t-sm-overflowX"></div>
<div class="t-sm-overflowY"></div>
<div class="t-sm-overflowScroll"></div>
<div class="t-sm-overflowHidden"></div>

<div class="t-md-overflow"></div>
<div class="t-md-overflowX"></div>
<div class="t-md-overflowY"></div>
<div class="t-md-overflowScroll"></div>
<div class="t-md-overflowHidden"></div>

<div class="t-lg-overflow"></div>
<div class="t-lg-overflowX"></div>
<div class="t-lg-overflowY"></div>
<div class="t-lg-overflowScroll"></div>
<div class="t-lg-overflowHidden"></div>
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
