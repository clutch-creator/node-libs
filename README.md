# Clutch Node Libraries

Node libraries polyfills and mocks to be used in a browser environment.

## Current polyfills and mocks

| lib name | polyfill implementation | mock implementation |
|:--------:|:----------------------:|:-------------------:|
| assert | [defunctzombie/commonjs-assert](https://github.com/defunctzombie/commonjs-assert) | --- |
| buffer | [feross/buffer](https://github.com/feross/buffer) | [buffer.js](https://github.com/webpack/node-libs-browser/blob/master/mock/buffer.js) |
| child_process | --- | --- |
| cluster | --- | --- |
| console | [Raynos/console-browserify](https://github.com/Raynos/console-browserify) | [console.js](https://github.com/webpack/node-libs-browser/blob/master/mock/console.js) |
| constants | [juliangruber/constants-browserify](https://github.com/juliangruber/constants-browserify) | --- |
| crypto | [crypto-browserify/crypto-browserify](https://github.com/crypto-browserify/crypto-browserify) | --- |
| dgram | --- | --- |
| dns | --- | [dns.js](https://github.com/webpack/node-libs-browser/blob/master/mock/dns.js) |
| domain | [bevry/domain-browser](https://github.com/bevry/domain-browser) | --- |
| events | [Gozala/events](https://github.com/Gozala/events) | --- |
| fs | --- | --- |
| http | [jhiesey/stream-http](https://github.com/jhiesey/stream-http) | --- |
| https | [substack/https-browserify](https://github.com/substack/https-browserify) | --- |
| module | --- | --- |
| net | --- | [net.js](https://github.com/webpack/node-libs-browser/blob/master/mock/net.js) |
| os | [CoderPuppy/os-browserify](https://github.com/CoderPuppy/os-browserify) | --- |
| path | [substack/path-browserify](https://github.com/substack/path-browserify) | --- |
| process | [shtylman/node-process](https://github.com/shtylman/node-process) | [process.js](https://github.com/webpack/node-libs-browser/blob/master/mock/process.js) |
| punycode | [bestiejs/punycode.js](https://github.com/bestiejs/punycode.js) | --- |
| querystring | [mike-spainhower/querystring](https://github.com/mike-spainhower/querystring) | --- |
| readline | --- | --- |
| repl | --- | --- |
| stream | [substack/stream-browserify](https://github.com/substack/stream-browserify) | --- |
| string_decoder | [rvagg/string_decoder](https://github.com/rvagg/string_decoder) | --- |
| sys | [defunctzombie/node-util](https://github.com/defunctzombie/node-util) | --- |
| timers | [jryans/timers-browserify](https://github.com/jryans/timers-browserify) | --- |
| tls | --- | [tls.js](https://github.com/webpack/node-libs-browser/blob/master/mock/tls.js) |
| tty | [substack/tty-browserify](https://github.com/substack/tty-browserify) | [tty.js](https://github.com/webpack/node-libs-browser/blob/master/mock/tty.js) |
| url | [defunctzombie/node-url](https://github.com/defunctzombie/node-url) | --- |
| util | [defunctzombie/node-util](https://github.com/defunctzombie/node-util) | --- |
| vm | [substack/vm-browserify](https://github.com/substack/vm-browserify) | --- |
| zlib | [devongovett/browserify-zlib](https://github.com/devongovett/browserify-zlib) | --- |
