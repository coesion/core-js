# @coesion/core-js

Artifact-only distribution for Coesion Core JS.

## Install

```bash
npm install @coesion/core-js
```

## Usage

```js
const { Route, Response } = require('@coesion/core-js');

Route.get('/', () => 'Core JS loaded from artifact package.');
Response.send();
```

## Notes

- This package is generated from the factory repository.
- Runtime entrypoints are `index.js` and `core.js`.
- Source-only directories like tests and scripts are excluded.
