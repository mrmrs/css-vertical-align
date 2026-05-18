# css-vertical-align

Functional CSS for vertical-align

## Filesize

| File | Size |
|------|------|
| `dist/vertical-align.css` | 1565 bytes |
| `dist/vertical-align.min.css` | 1119 bytes (248 Gzipped) |

## Install

```sh
npm install css-vertical-align
```

## Usage

### Import

```css
@import "css-vertical-align";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-vertical-align/dist/vertical-align.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-vertical-align/dist/vertical-align.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.v-base` | `vertical-align: baseline;` |
| `.v-sub` | `vertical-align: sub;` |
| `.v-sup` | `vertical-align: super;` |
| `.v-txt-top` | `vertical-align: text-top;` |
| `.v-txt-btm` | `vertical-align: text-bottom;` |
| `.v-mid` | `vertical-align: middle;` |
| `.v-top` | `vertical-align: top;` |
| `.v-btm` | `vertical-align: bottom;` |
| `.v-base-s` | `vertical-align: baseline;` |
| `.v-sub-s` | `vertical-align: sub;` |
| `.v-sup-s` | `vertical-align: super;` |
| `.v-txt-top-s` | `vertical-align: text-top;` |
| `.v-txt-btm-s` | `vertical-align: text-bottom;` |
| `.v-mid-s` | `vertical-align: middle;` |
| `.v-top-s` | `vertical-align: top;` |
| `.v-btm-s` | `vertical-align: bottom;` |
| `.v-base-m` | `vertical-align: baseline;` |
| `.v-sub-m` | `vertical-align: sub;` |
| `.v-sup-m` | `vertical-align: super;` |
| `.v-txt-top-m` | `vertical-align: text-top;` |
| `.v-txt-btm-m` | `vertical-align: text-bottom;` |
| `.v-mid-m` | `vertical-align: middle;` |
| `.v-top-m` | `vertical-align: top;` |
| `.v-btm-m` | `vertical-align: bottom;` |
| `.v-base-l` | `vertical-align: baseline;` |
| `.v-sub-l` | `vertical-align: sub;` |
| `.v-sup-l` | `vertical-align: super;` |
| `.v-txt-top-l` | `vertical-align: text-top;` |
| `.v-txt-btm-l` | `vertical-align: text-bottom;` |
| `.v-mid-l` | `vertical-align: middle;` |
| `.v-top-l` | `vertical-align: top;` |
| `.v-btm-l` | `vertical-align: bottom;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.v-base-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/vertical-align.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/vertical-align.css` — formatted
- `dist/vertical-align.min.css` — minified

## License

MIT
