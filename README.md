<div align="center">
  <div>
    <img width="500" src="https://res.cloudinary.com/adonisjs/image/upload/q_100/v1532274184/Dimer_Readme_Banner_lyy7wv.svg" alt="Dimer App">
  </div>
  <br>
  <p>
    <a href="https://dimerapp.com/what-is-dimer">
      Dimer is an open source project and CMS to help you publish your documentation online.
    </a>
  </p>
  <br>
  <p>
    <sub>We believe every project/product is incomplete without documentation. <br /> We want to help you publish user facing documentation, without worrying <code>about tools or code</code> to write.</sub>
  </p>
  <br>
</div>

# Dimer Image
> Serve images detected via @dimerapp/image

[![travis-image]][travis-url]
[![npm-image]][npm-url]

This package can be used as a middleware to serve assets from the `dist/__assets` directory

## Installation

```shell
npm i @dimerapp/assets-midddleware

# yarn
yarn add @dimerapp/assets-midddleware
```

## Usage

```js
const assetsMiddleware = require('@dimerapp/assets-midddleware')
const httpServer = require('@dimerapp/http-server')

const { router } = httpServer()
const basePath = __dirname

route.use(assetsMiddleware(basePath))
```

## Usage

## Change log

The change log can be found in the [CHANGELOG.md](https://github.com/dimerapp/assets-middleware/CHANGELOG.md) file.

## Contributing

Everyone is welcome to contribute. Please take a moment to review the [contributing guidelines](CONTRIBUTING.md).

## Authors & License
[thetutlage](https://github.com/thetutlage) and [contributors](https://github.com/dimerapp/assets-middleware/graphs/contributors).

MIT License, see the included [MIT](LICENSE.md) file.

[travis-image]: https://img.shields.io/travis/dimerapp/assets-middleware/master.svg?style=flat-square&logo=travis
[travis-url]: https://travis-ci.org/dimerapp/assets-middleware "travis"

[npm-image]: https://img.shields.io/npm/v/@dimerapp/assets-middleware.svg?style=flat-square&logo=npm
[npm-url]: https://npmjs.org/package/@dimerapp/assets-middleware "npm"
