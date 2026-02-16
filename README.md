# css-vertical-align

Functional CSS for vertical-align

## Filesize

| File | Size |
|------|------|
| `dist/vertical-align.css` | 1625 bytes |
| `dist/vertical-align.min.css` | 1179 bytes (248 Gzipped) |

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
| `.v-baseline` | `vertical-align: baseline;` |
| `.v-sub` | `vertical-align: sub;` |
| `.v-sup` | `vertical-align: super;` |
| `.v-text-top` | `vertical-align: text-top;` |
| `.v-text-bottom` | `vertical-align: text-bottom;` |
| `.v-middle` | `vertical-align: middle;` |
| `.v-top` | `vertical-align: top;` |
| `.v-bottom` | `vertical-align: bottom;` |
| `.v-baseline-s` | `vertical-align: baseline;` |
| `.v-sub-s` | `vertical-align: sub;` |
| `.v-sup-s` | `vertical-align: super;` |
| `.v-text-top-s` | `vertical-align: text-top;` |
| `.v-text-bottom-s` | `vertical-align: text-bottom;` |
| `.v-middle-s` | `vertical-align: middle;` |
| `.v-top-s` | `vertical-align: top;` |
| `.v-bottom-s` | `vertical-align: bottom;` |
| `.v-baseline-m` | `vertical-align: baseline;` |
| `.v-sub-m` | `vertical-align: sub;` |
| `.v-sup-m` | `vertical-align: super;` |
| `.v-text-top-m` | `vertical-align: text-top;` |
| `.v-text-bottom-m` | `vertical-align: text-bottom;` |
| `.v-middle-m` | `vertical-align: middle;` |
| `.v-top-m` | `vertical-align: top;` |
| `.v-bottom-m` | `vertical-align: bottom;` |
| `.v-baseline-l` | `vertical-align: baseline;` |
| `.v-sub-l` | `vertical-align: sub;` |
| `.v-sup-l` | `vertical-align: super;` |
| `.v-text-top-l` | `vertical-align: text-top;` |
| `.v-text-bottom-l` | `vertical-align: text-bottom;` |
| `.v-middle-l` | `vertical-align: middle;` |
| `.v-top-l` | `vertical-align: top;` |
| `.v-bottom-l` | `vertical-align: bottom;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.v-baseline-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/vertical-align.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/vertical-align.css` — formatted
- `dist/vertical-align.min.css` — minified

## License

MIT
