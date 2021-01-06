# <img align="center" src="https://avatars2.githubusercontent.com/u/76873423" width="96" height="96" /> Javascript Starter Template

This project includes a sample [LitElement](https://lit-element.polymer-project.org) web component using looksee with [snowpack](https://www.snowpack.dev).

## Setup

Install dependencies:

```bash
npm i
```

## Testing

Tests can be run with the `test` script:

```bash
npm test
```

## Dev Server

This sample uses [snowpack](https://www.snowpack.dev) for previewing the project without additional build steps.

Snowpack’s [dev server](https://www.snowpack.dev/concepts/dev-server) is an instant dev environment for unbundled development. It will build a file only when it’s requested by the browser. That means that it can start up instantly (usually in <50ms) and scale to infinitely large projects without slowing down. In contrast, it’s common to see 30+ second dev startup times when building large apps with a traditional bundler.

Snowpack supports JSX & TypeScript source code by default.

The dev server can be run with the `start` script:

```bash
npm start
```

###### Copyright (c) 2021 Allan Mobley Jr. All rights reserved.
###### Licensed under the [MIT](./LICENSE) license.
