# css-font-variant 1.0.6

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

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-font-variant
```

ssh:
```
git clone git@github.com:tachyons-css/css-font-variant.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-font-variant";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-font-variant@1.0.6/css/css-font-variant.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-font-variant">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

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

ISC

