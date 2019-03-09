# react-counter-input

[![Travis][build-badge]][build]
[![npm package][npm-badge]][npm]
[![Coveralls][coveralls-badge]][coveralls]
[![Storybook][storybook-badge]][storybook]

## Installation and Usage

The easiest way to use `react-counter-input` is to install it from npm:

```
npm install react-counter-input
```

Then use it in your app:

```javascript
import React from "react";
import CounterInput from "react-counter-input";

class App extends React.Component {
  render() {
    return (
      <CounterInput
        min={0}
        max={10}
        onCountChange={count => console.log(count)}
      />
    );
  }
}
```

For more examples, check out the [Storybook][storybook].

## Props

### `count`
> `number` | optional, defaults to `0`

### onCountChange
> `function` | optional

### min
> `number` | optional

### max
> `number` | optional

### children
>`function` | optional

[build-badge]: https://img.shields.io/travis/user/repo/master.png?style=flat-square
[build]: https://travis-ci.org/user/repo

[npm-badge]: https://img.shields.io/npm/v/npm-package.png?style=flat-square
[npm]: https://www.npmjs.org/package/npm-package

[coveralls-badge]: https://img.shields.io/coveralls/user/repo/master.png?style=flat-square
[coveralls]: https://coveralls.io/github/user/repo

[storybook-badge]: https://github.com/storybooks/brand/blob/master/badge/badge-storybook.svg
[storybook]: https://peaceful-leavitt-38971b.netlify.com
