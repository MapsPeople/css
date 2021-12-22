# MapsIndoors CSS

CSS button component and helpers using MapsIndoors Design Tokens ([midt](https://www.npmjs.com/package/@mapsindoors/midt))

The component is using the BEM methodology.

See the demo page (index.html) for an overview.

## Release a new version

To release a new version:

1. Make your changes and commit them
1. Update the version number in `package.json` based on [Semantic Versioning](https://semver.org)
1. Tag the last commit with the version number in this format: `v1.2.3`
1. Push your commits with `git push --follow-tags`
1. GitHub Actions on the repo will create a Release with the tag's version number and push that versioned release to npm

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
