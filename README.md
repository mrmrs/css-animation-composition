# css-animation-composition

Functional CSS for animation-composotion

## Filesize

| File | Size |
|------|------|
| `dist/animation-composition.css` | 769 bytes |
| `dist/animation-composition.min.css` | 593 bytes (164 Gzipped) |

## Install

```sh
npm install css-animation-composition
```

## Usage

### Import

```css
@import "css-animation-composition";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-animation-composition/dist/animation-composition.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-animation-composition/dist/animation-composition.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.a-replace` | `animation-composition: replace;` |
| `.a-add` | `animation-play-state: add;` |
| `.a-accumulate` | `animation-play-state: accumulate;` |
| `.a-replace-s` | `animation-composition: replace;` |
| `.a-add-s` | `animation-play-state: add;` |
| `.a-accumulate-s` | `animation-play-state: accumulate;` |
| `.a-replace-m` | `animation-composition: replace;` |
| `.a-add-m` | `animation-play-state: add;` |
| `.a-accumulate-m` | `animation-play-state: accumulate;` |
| `.a-replace-l` | `animation-composition: replace;` |
| `.a-add-l` | `animation-play-state: add;` |
| `.a-accumulate-l` | `animation-play-state: accumulate;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.a-replace-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/animation-composition.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/animation-composition.css` — formatted
- `dist/animation-composition.min.css` — minified

## License

MIT
