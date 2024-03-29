<div align="center">
  <a href="https://tronite.com" target="_blank"><img src="https://tronite.com/images/logo.png" width="150" /></a>
  <h1>@tronite/prettier-config</h1>
</div>

This package provides [Prettier](https://prettier.io/) configuration for [Tronite](https://tronite.com) projects. It is intended to be used with [@tronite/eslint-config](https://github.com/tronite/eslint-config) and [@tronite/tsconfig](https://github.com/tronite/tsconfig).

## Installation

To install this package, run the following command:

```sh
pnpm add -D @tronite/prettier-config
```

You will also need to install the following peer dependencies:

```sh
pnpm add -D prettier
```

## Usage

Add the following to your `.prettierrc.js` file:

```js
module.exports = require('@tronite/prettier-config');
```
