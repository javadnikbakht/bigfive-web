# bigfive-web

<img src="https://github.com/rubynor/bigfive-web/blob/master/static/icon.png?raw=true" width="160" height="160" alt="Bigfive logo" align="right">

Website for five factor model of personality based on work from [IPIP-NEO-PI](https://github.com/kholia/IPIP-NEO-PI).

Tests and evaluation is gathered from [ipip.ori.org](http://ipip.ori.org).

The frontend is written in [nodejs](https://nodejs.org) using the
[Nuxt.js](https://nuxtjs.org/) framework.

## Preview

![Preview](https://media4.giphy.com/media/MWsRzFD3hrsXi9tKzu/giphy.gif)

## Installation

Download and install [nodejs](https://nodejs.org),


Make sure nodejs version is equal or greater than 12

The results are saved to a [mongodb](https://www.mongodb.com/) database, so for a full test you either need a running mongodb or an instance at [mlab](https://mlab.com/)

## Development

add .env file

```
MONGODB_URI=mongodb://<your-mongodb-url>
MONGODB_COLLECTION=results
BASE_URL=http://localhost:3000
```
Run the setup script to install all dependencies

```
yarn run setup
```

### Compiles and hot-reloads for development
```
yarn dev
```

### Run your unit tests
```
yarn test
```

### Lint

```
yarn lint
yarn lintfix
```
## License

[MIT](LICENSE)

