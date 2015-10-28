# cityjs

Inspired by [wingchen/citipy](https://github.com/wingchen/citipy) , a simple npm module to find the nearest city by coordinates 

## Credits
- KD-TREE module [luk-/node-kdt](https://github.com/luk-/node-kdt)
- City coordinates data from [Maxmind](www.maxmind.com/en/free-world-cities-database)

## Basic use

```javascript
var cityjs = require('cityjs');

var city = cityjs.nearest({lat:37.77,long:-122.41});
console.log(city); // {"country":"us","city":"san francisco","lat":37.775,"long":-122.4183333}
```

## Unit test

``` bash
  $ npm install -g mocha
  $ npm test
```
