# xico2k-scss-mixins

[![NPM](https://nodei.co/npm/xico2k-scss-mixins.png?downloads=true&downloadRank=true)](https://npmjs.org/package/xico2k-scss-mixins)

This is my personal mixins.

## Installation
With [npm](https://www.npmjs.com):
```
$ npm i xico2k-scss-mixins
```
or with [yarn](https://yarnpkg.com):
```
$ yarn add xico2k-scss-mixins
```

## Usage

On your SCSS file just add:

```css
@import "~xico2k-scss-mixins/mixins";
```

## Methods and Examples

```scss
/* Simple perfixes like compass */
@include transition(left .2s ease-in-out);
@include transform(rotate(180deg));
@include appearance(none);
@include filter(brightness(0.4));
@include translateX(10px);
@include translateY(20px);
@include translate(10px 20px);
@include box-shadow(3px 3px 5px 6px #ccc);

/* Standard clearfix */
@include clearfix();

/* Flexbox usage with the prefixes */
@include flex();
@include flex-direction();
@include flex-wrap();
@include flex-flow();
@include order();
@include flex-grow();
@include flex-shrink();
@include flex-basis();
@include justify-content();
@include align-content();
@include align-items();
@include align-self();

@include flexbox(); /* Use on the wrapper */
@include flexbox-float(); /* Use on the elems inside of the wrapper */

/* CSS Arows */
@include arrow(top, 10px, 5px, #000); /* Orientation (top; right; bottom; left), Width, Height, Color */
@include arrow-hover(top, #FF0) /* To use on the :hover method */
