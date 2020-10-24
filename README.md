# Covid19-Global

[![Stats](https://img.shields.io/npm/dt/covid19-global.svg?maxAge=3600)](https://roalia.js.org)

# Covid 19

- Shows cases in the world and countries.

---

> Packages used : axios,cheerio

> Data : [Data Website](https://www.worldometers.info/coronavirus)

And of course covid19 api itself is open source with a [public repository](https://github.com/Roaliia/covid19)
 on GitHub.

### Installation

Covid19 Api requires [Node.js](https://nodejs.org/) v4+ to run.

Install the package and start the server.

```sh
$ npm install covid19-global
```

### Usage

##### Global data
 ---
```js
const corona = require('covid19-global');
let stats = await corona.covid19() // Global Data
let stats = await corona.country('World') // World Data
```

##### Country Data
---
```js
const corona = require('covid19-global');
let stats = await corona.country('Turkey') // Country Data
```
