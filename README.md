# epithet

Very simple random name generator.

## Usage

```js
var epithet = require('epithet');

myReallyGreatName = epithet.choose();
```

## Methods

### `.choose()`

`epithet.choose()` returns a string in the form of adjective-noun.

### `.randomWord(opt)`

Returns a random **string**.

An optional argument specifies the word type and can be one of `adjective` or `noun`. If no argument is provided, a type of `noun` is assumed.

### `.returnDict(opt)`

Returns an **array** of all the words of a certain type in epithet’s dictionary.

An optional argument specifies the word type and can be one of `adjective` or `noun`. If no argument is provided, a type of `noun` is assumed.

## Acknowledgements

Based on [moniker](https://github.com/weaver/moniker/)’s dictionaries.
