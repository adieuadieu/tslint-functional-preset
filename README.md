# tslint-functional-preset

A "functional" preset for [TSLint](https://github.com/palantir/tslint) with some crazy defaults that promote a functional, immutable, and declarative programming style. It's mostly a convenience preset around the rules provided by [tslint-immutable](https://github.com/jonaskello/tslint-immutable).

## Setup

Install with npm or yarn:

```bash
yarn add tslint-functional-preset --dev
```

Add the following to your project's `tslint.json`:

```json
{
  "extends": ["tslint-functional-preset"]
}
```
