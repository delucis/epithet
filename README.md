# epithet

Very simple random name generator.

Compatible with [browserify](https://www.npmjs.com/package/browserify).

## Usage

```js
var epithet = require('epithet');

myReallyGreatName = epithet.choose();
```

## Methods

### `.choose(opt)`

`epithet.choose()` returns a **string** combining an adjective and a noun.

An optional argument specifies the separator between the adjective and the noun. If no argument is provided, a default hyphen is used: `-`.

### `.randomWord(opt)`

Returns a random **string**.

An optional argument specifies the word type and can be one of `adjective` or `noun`. If no argument is provided, a type of `noun` is assumed.

### `.returnDict(opt)`

Returns an **array** of all the words of a certain type in epithet’s dictionary.

An optional argument specifies the word type and can be one of `adjective` or `noun`. If no argument is provided, a type of `noun` is assumed.

## Acknowledgements

Based on [moniker](https://github.com/weaver/moniker/)’s dictionaries.
