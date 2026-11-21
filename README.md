# @zeekay/rollup-plugin-stylus

[![Open in Hanzo](https://hanzo.app/badges/open-in-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/rollup-plugin-stylus&ref=master&action=open) [![Edit with Hanzo](https://hanzo.app/badges/edit-with-hanzo.svg)](https://hanzo.app/dev/open?repo=github.com/zeekay/rollup-plugin-stylus&ref=master&action=edit)

[![Build Status](https://travis-ci.org/zeekay/rollup-plugin-stylus.svg?branch=master)](https://travis-ci.org/zeekay/rollup-plugin-stylus)

A Rollup.js plugin to compile Stylus.

## Install

```bash
npm install @zeekay/rollup-plugin-stylus --save-dev
```

## Usage

Add the following code to your project's `rollup.config.js`:

```js
import stylus from '@zeekay/rollup-plugin-stylus';

export default {
  entry: 'index.js',
  plugins: [
    stylus({
      plugins: [],
    })
  ]
};
```

## License

MIT
