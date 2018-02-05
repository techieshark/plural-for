# plural-for: tiny node module to pluralize English words

This is meant to be small and stupidly simple.

For the absolutely simplest alternative, see [sorp](https://www.npmjs.com/package/sorp).

For smarter/bigger options, you've got:

* [pluralise](https://www.npmjs.com/package/pluralise)
* [plrl](https://github.com/mgduk/plrl)
* [pluralize](https://github.com/blakeembrey/pluralize)
* [plur](https://www.npmjs.com/package/plur)


## Install

```
npm install --save plural-for
```

## Example Usage

```
var pluralFor = require('plural-for')
import {numToText} from 'zero-to-nine'

let nOcelots = 0
let nWolves = 2

console.log(`There will be ${numToText(nOcelots)} ${pluralFor(nOcelots, 'ocelot')} left after building the wall.`)
// output: "There will be zero ocelots left after building the wall."

console.log(`There will be only ${numToText(nWolves)} Mexican gray ${pluralFor(nWolves, 'wolf', 'wolves')} left, sadly.`)
// output: There will be only one Mexican gray wolves left, sadly.

```
See also: more about [biodiversity threats example](https://phys.org/news/2017-08-border-wall-endangered-species-expert.html).

