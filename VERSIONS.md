# Versions

You can control what version of React.js (and JSXTransformer) is used by `react-rails`:

- Use the [bundled version](#bundled-versions) that comes with the gem
- [Drop in a copy](#drop-in-version) of React.js

## Bundled Versions

| Gem      | React.js |
|----------|----------|
| master   | 0.13.3   |
| 1.1.0    | 0.13.3   |
| 1.0.0    | ~> 0.13  |
| 0.13.0.0 | 0.13.0   |
| 0.12.2.0 | 0.12.2   |
| 0.12.1.0 | 0.12.1   |
| 0.12.0.0 | 0.12.0   |

## Drop-in Version

You can also provide your own copies of React.js and JSXTransformer. Just add `react.js` or `JSXTransformer.js` (case-sensitive) files to the asset pipeline (eg,  `app/assets/vendor/`).
