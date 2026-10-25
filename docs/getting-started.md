# Getting started

## Install

```bash
npm install polaris-spacing
```

## Distribution files

- `dist/css/main.min.css`

## Integration

Load the chosen compiled stylesheet in your page after any base styles whose values you want the plugin to override. The plugin provides CSS; no plugin JavaScript initialization is required.

When using a package manager, import or copy the appropriate compiled asset from `node_modules/polaris-spacing/dist/`. Keep source Sass files available when customizing the plugin.

## Important distinctions

- `src/` contains development source.
- `dist/` contains compiled assets intended for consumption.
- `index.js` is not documented here as a browser UI initialization API.
- Existing public CSS names and, where applicable, JavaScript APIs should remain stable during maintenance.
