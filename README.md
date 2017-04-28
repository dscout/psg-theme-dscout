# psg-theme-dscout

dscout [postcss-style-guide] theme

## Install

```shell
$ yarn add --dev psg-theme-dscout
```

## Usage

In your `postcss.config.js` set the `theme` and `themePath` options for
postcss-style-guide:

```javascript
require('postcss-style-guide')({
  project: projectName,
  dest: 'styleguide/index.html',
  theme: 'dscout',
  themePath: 'node_modules/psg-theme-dscout'
})
```

## Theme

![Default style guide design](./minimal-theme.png)

## License

The MIT License (MIT)

[postcss-style-guide]: https://github.com/morishitter/postcss-style-guide
[minimal]: https://github.com/blivesta/psg-theme-minimal
