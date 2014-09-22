# CSS FONT VARIANT

  Mobile-first classes for css-font-variant.
  Set the desired css-font-variant on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-font-variant
```
View on [npm](https://www.npmjs.org/package/css-font-variant)


## File Size

728B font-variant.css
558B font-variant.min.css 
182B minified and gzipped

## The Code
```
.fv-norm    { font-variant: normal; }
.fv-sc,
.small-caps { font-variant: small-caps; }
.fv-i       { font-variant: inherit; }

@media screen and (min-width: 48em) {
  .fv-norm-ns    { font-variant: normal; }
  .fv-sc-ns,
  .small-caps-ns { font-variant: small-caps; }
  .fv-i-ns       { font-variant: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .fv-norm-m    { font-variant: normal; }
  .fv-sc-m,
  .small-caps-m { font-variant: small-caps; }
  .fv-i-m       { font-variant: inherit; }
}

@media screen and (min-width: 64em)  {
  .fv-norm-l    { font-variant: normal; }
  .fv-sc-l,
  .small-caps-l { font-variant: small-caps; }
  .fv-i-l       { font-variant: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

