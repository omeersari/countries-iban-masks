# countries-iban-masks

This package provides IBAN masks for various countries. The iban_masks.json file contains information about each country's IBAN mask, including the country name, ISO code, flag URL, and IBAN mask.

## Installation

```bash
npm install countries-iban-masks
```

## Usage

```javascript
const countries = require('countries-iban-masks')

console.log(ibans.find(({ name }) => name === 'Turkey'))
// {
//    "name": "Turkey",
//    "iso": "TR",
//    "flag": "https://cdn.kcak11.com/CountryFlags/countries/tr.svg",
//    "iban_mask": "TR## #### #### #### #### #### ##"
// }
```

## Contributing

If you want to contribute to this project, feel free to open issues or submit pull requests.


## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
