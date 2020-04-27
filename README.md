# MapsIndoors CSS

CSS button component and helpers using MapsIndoors Design Tokens ([midt](https://www.npmjs.com/package/@mapsindoors/midt))

The component is using the BEM methodology.

See the demo page (index.html) for an overview.

## mi-button

The `.mi-button` block class is used for styling buttons.

Basic example:

```html
<button type="button" class="mi-button mi-button--primary">Click me</button>
```

Variants:

- `mi-button--primary`
- `mi-button--base`
- `mi-button--danger`
- `mi-button--outline`
- `mi-button--link`.

## Helpers

The `helpers.css`-file is a range of _CSS utility classes_ that each serve a particular purpose.

Example:

```html
<body class="debug">
```

Sets golden yellow lines around all elements on the page for easier debugging (when using `.flex` for instance).

Other examples:

- `.max-height-xx-large` to set a `max-height` of `40px`
- `.width-none` to set a `width` of `none`
- `.inline-flex` to set `display: inline-flex;`
- `.margin-auto` to center items with `margin-left` and `margin-right` set to `auto`
