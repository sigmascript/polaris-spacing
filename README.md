# Polaris Spacing

**Version 1.3.0** · Polaris UI plugin · MIT license

Responsive padding and margin utility classes.

This repository contains the plugin's source and compiled distribution assets. It is maintained separately from [Polaris Core](https://github.com/sigmascript/polaris-core).

## Install

```bash
npm install polaris-spacing
```

## Get started

Load the chosen compiled stylesheet in your page after any base styles whose values you want the plugin to override. The plugin provides CSS; no plugin JavaScript initialization is required.

Available production assets in this repository:

- `dist/css/main.min.css`

For example, use the appropriate stylesheet from `node_modules/polaris-spacing/dist/css/` in your application's asset pipeline. A plain HTML project can also copy the required compiled files into its public assets.

## Development

```bash
npm install
npm run css
```

For the complete list of production and watch commands, see [Development](docs/development.md). Development dependencies remain in the plugin repository; they do not need to be deployed with a production website.

## Documentation

- [Documentation index](docs/README.md)
- [Getting started](docs/getting-started.md)
- [Development and build commands](docs/development.md)
- [Changelog](CHANGELOG.md)

## Compatibility

The development toolchain uses Polaris Core 1.0.6 and Sass 1.105.2. Production and development CSS builds passed, and the refreshed dependency audit reported zero vulnerabilities.

## Support and license

Report issues through the [repository issue tracker](https://github.com/sigmascript/polaris-spacing/issues). Licensed under MIT; see `LICENSE`.
