# list-of-currencies

[![npm](https://img.shields.io/npm/v/list-of-currencies.svg)](https://www.npmjs.com/package/list-of-currencies)


List of currencies based on openexchangerates.org in JSON format.
The list is most up to date and only include real life currencies (no historical data or currencies that no longer exist).

## Installation

### NPM
```bash
$ npm i list-of-currencies
```

### ES6
```js
import Currencies from 'list-of-currencies'

new Vue({
  components: {
    CurrenciesList: Currencies
  }
})
```

## Usage

You can either use the simple list (default):
```
[
  "AED",
  "AFN",
  "ALL",
  "AMD",
  "ANG",
  "AOA",
  "ARS",
  "AUD",
  "AWG",
  ...
```

Or list with names:
```
{
  "AED": "United Arab Emirates Dirham",
  "AFN": "Afghan Afghani",
  "ALL": "Albanian Lek",
  "AMD": "Armenian Dram",
  "ANG": "Netherlands Antillean Guilder",
  "AOA": "Angolan Kwanza",
  "ARS": "Argentine Peso",
  "AUD": "Australian Dollar",
  "AWG": "Aruban Florin",
  ...
```


If you want to use list with names, import the JSON as follows:
```js
import Currencies from 'list-of-currencies/currencies-with-names.json'
```
