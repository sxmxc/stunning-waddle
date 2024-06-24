# Status

[![Deploy Theme](https://github.com/sxmxc/stunning-waddle/actions/workflows/deploy-theme.yml/badge.svg)](https://github.com/sxmxc/stunning-waddle/actions/workflows/deploy-theme.yml)

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/edge.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Copyright & License

Copyright (c) 2013-2023 Ghost Foundation - Released under the [MIT license](LICENSE).
