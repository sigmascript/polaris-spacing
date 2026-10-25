# Development

## Prerequisites

Install Node.js and the package's development dependencies:

```bash
npm install
```

The current project scripts are:

| Script | Command |
|---|---|
| `npm run css` | `sass src/scss/main.scss dist/css/main.min.css --style compressed --load-path=node_modules --no-source-map` |
| `npm run css-dev` | `sass src/scss/main.scss dist/css/main.css --watch --load-path=node_modules` |

## Production and watch commands

One-shot commands: `npm run css`.

Watch commands: `npm run css-dev`. Watchers continue running until stopped with `Ctrl+C`.

## Release checks

1. Run `npm audit` and inspect any reported advisories.
2. Run all applicable one-shot build commands.
3. Check watch commands individually, then stop each with `Ctrl+C`.
4. Review `git diff --stat`, `git diff --check`, and generated `dist/` changes.
5. Run `npm pack --dry-run` to inspect published contents.
6. Verify compatibility with the intended Polaris Core version before selecting a new release version.

The current `npm test` script is a placeholder, not a test suite; do not treat it as a passing test. Avoid changing public class names, Sass customization names, or JavaScript interfaces without a compatibility review.
