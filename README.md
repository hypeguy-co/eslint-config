
## Installation

```
$ npm install --save-dev eslint @hypeguy/eslint-config
```


## Usage

Once the `@hypeguy/eslint-config` package is installed, you can use it by specifying `google` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "@hypeguy/eslint-config",
  "rules": {
    // Additional, per-project rules...
  }
}
```
