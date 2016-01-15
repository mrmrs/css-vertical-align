# css-vertical-align 0.0.6

Css module of single purpose classes for vertical align

#### Stats

289 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-vertical-align
```

#### With Git

```
git clone https://github.com/tachyons-css/css-vertical-align
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-vertical-align";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-vertical-align">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   VERTICAL ALIGN
*/
.v-base { vertical-align: baseline; }
.v-sub { vertical-align: sub; }
.v-sup { vertical-align: super; }
.v-txt-top { vertical-align: text-top; }
.v-txt-btm { vertical-align: text-bottom; }
.v-mid { vertical-align: middle; }
.v-top { vertical-align: top; }
.v-btm { vertical-align: bottom; }
@media screen and (min-width: 48em) {
 .v-base-ns { vertical-align: baseline; }
 .v-sub-ns { vertical-align: sub; }
 .v-sup-ns { vertical-align: super; }
 .v-txt-top-ns { vertical-align: text-top; }
 .v-txt-btm-ns { vertical-align: text-bottom; }
 .v-mid-ns { vertical-align: middle; }
 .v-top-ns { vertical-align: top; }
 .v-btm-ns { vertical-align: bottom; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .v-base-m { vertical-align: baseline; }
 .v-sub-m { vertical-align: sub; }
 .v-sup-m { vertical-align: super; }
 .v-txt-top-m { vertical-align: text-top; }
 .v-txt-btm-m { vertical-align: text-bottom; }
 .v-mid-m { vertical-align: middle; }
 .v-top-m { vertical-align: top; }
 .v-btm-m { vertical-align: bottom; }
}
@media screen and (min-width: 64em) {
 .v-base-l { vertical-align: baseline; }
 .v-sub-l { vertical-align: sub; }
 .v-sup-l { vertical-align: super; }
 .v-txt-top-l { vertical-align: text-top; }
 .v-txt-btm-l { vertical-align: text-bottom; }
 .v-mid-l { vertical-align: middle; }
 .v-top-l { vertical-align: top; }
 .v-btm-l { vertical-align: bottom; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

