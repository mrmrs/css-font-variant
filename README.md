# css-font-variant

Functional CSS for font-variant

## Filesize

| File | Size |
|------|------|
| `dist/font-variant.css` | 699 bytes |
| `dist/font-variant.min.css` | 519 bytes (165 Gzipped) |

## Install

```sh
npm install css-font-variant
```

## Usage

### Import

```css
@import "css-font-variant";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-font-variant/dist/font-variant.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-font-variant/dist/font-variant.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.fv-norm` | `font-variant: normal;` |
| `.small-caps` | `font-variant: small-caps;` |
| `.fv-i` | `font-variant: inherit;` |
| `.fv-norm-s` | `font-variant: normal;` |
| `.small-caps-s` | `font-variant: small-caps;` |
| `.fv-i-s` | `font-variant: inherit;` |
| `.fv-norm-m` | `font-variant: normal;` |
| `.small-caps-m` | `font-variant: small-caps;` |
| `.fv-i-m` | `font-variant: inherit;` |
| `.fv-norm-l` | `font-variant: normal;` |
| `.small-caps-l` | `font-variant: small-caps;` |
| `.fv-i-l` | `font-variant: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.fv-norm-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/font-variant.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/font-variant.css` — formatted
- `dist/font-variant.min.css` — minified

## License

MIT
