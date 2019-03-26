# react-reading-progress-plus

[![npm version](https://img.shields.io/npm/v/react-reading-progress-plus.svg?style=flat-square)](https://www.npmjs.com/package/react-reading-progress-plus)
[![travis](http://img.shields.io/travis/petekeller2/react-reading-progress.svg?style=flat-square)](https://travis-ci.org/petekeller2/react-reading-progress)
[![dependencies](http://img.shields.io/david/petekeller2/react-reading-progress.svg?style=flat-square)](https://github.com/petekeller2/react-reading-progress)
[![DevDependencies](http://img.shields.io/david/dev/petekeller2/react-reading-progress.svg?style=flat-square)](https://github.com/petekeller2/react-reading-progress)
[![License](http://img.shields.io/npm/l/react-reading-progress.svg?style=flat-square)](https://github.com/petekeller2/react-reading-progress)

> Reading progress bar component

[Demo](http://makotot.github.io/react-reading-progress/)

## Install

```sh
$ npm i react-reading-progress-plus
```

## Usage

```js
import ReadingProgress from 'react-reading-progress-plus'

...

<ReadingProgress targetEl="#target-el" />

<article id="target-el">
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Vel pharetra vel turpis nunc. Ut sem viverra aliquet eget sit amet tellus. Lacus suspendisse faucibus interdum posuere lorem ipsum dolor sit. In mollis nunc sed id semper risus in hendrerit gravida. Eleifend donec pretium vulputate sapien nec sagittis aliquam malesuada. Amet purus gravida quis blandit. Et ultrices neque ornare aenean euismod elementum nisi quis. Vitae aliquet nec ullamcorper sit amet.
</article>
```

## Props

### `targetEl={ String }`

Target article's selector. If this prop is not specified, `document.body` will be used.

### `rootEl={ String }`

Root element selector. If this prop is not specified, `window` will be used.

### `hideNoAndFullProgress={ Boolean }`

If this is set to true, the progress bar will be hidden if 
the progress is at 0 or max progress.

## License

MIT
