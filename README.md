# css-font-variant 0.0.7

Css module of single purpose classes for font variant

#### Stats

210 | 16 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-font-variant
```

#### With Git

```
git clone https://github.com/tachyons-css/css-font-variant
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-font-variant";
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
<link rel="stylesheet" href="path/to/module/css/css-font-variant">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FONT VARIANT
*/
.fv-norm { font-variant: normal; }
.fv-sc, .small-caps { font-variant: small-caps; }
.fv-i { font-variant: inherit; }
@media screen and (min-width: 48em) {
 .fv-norm-ns { font-variant: normal; }
 .fv-sc-ns, .small-caps-ns { font-variant: small-caps; }
 .fv-i-ns { font-variant: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fv-norm-m { font-variant: normal; }
 .fv-sc-m, .small-caps-m { font-variant: small-caps; }
 .fv-i-m { font-variant: inherit; }
}
@media screen and (min-width: 64em) {
 .fv-norm-l { font-variant: normal; }
 .fv-sc-l, .small-caps-l { font-variant: small-caps; }
 .fv-i-l { font-variant: inherit; }
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

