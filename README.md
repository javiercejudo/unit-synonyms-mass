# unit-synonyms-mass

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-mass.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-mass)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-mass/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-mass?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-mass/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-mass)

Mass units synonyms

## Install

    npm i unit-synonyms-mass

## Units

- [Kilogram](https://en.wikipedia.org/wiki/Kilogram)
- [Tonne](https://en.wikipedia.org/wiki/Tonne)
- [Gram](https://en.wikipedia.org/wiki/Gram)
- [Milligram](https://en.wikipedia.org/wiki/Milligram)
- [Microgram](https://en.wikipedia.org/wiki/Microgram)
- [Long ton](https://en.wikipedia.org/wiki/Long_ton)
- [Short ton](https://en.wikipedia.org/wiki/Short_ton)
- [Stone](https://en.wikipedia.org/wiki/Stone_(unit))
- [Pound](https://en.wikipedia.org/wiki/Pound_(mass))
- [Ounce](https://en.wikipedia.org/wiki/Ounce)

## Usage

```js
var synonyms = require('unit-synonyms-mass').synonyms;

synonyms['kg']; // => kilogram
synonyms['grammes']; // => gram
synonyms['stones']; // => stone
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
