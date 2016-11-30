# someWhere

Countries + Provinces/States. Populate those province and country dropdowns quickly with this one WEIRD trick!

This repo was adapted from: [substack/provinces](https://github.com/substack/provinces)

# Completeness

This module currently has states/provinces for:

* United States (US)
* United Kingdom (GB)
* Canada (CA)
* Mexico (MX)
* Australia (AU)
* China (CN)
* Germany (DE)
* Belgium (BE)
* Netherlands (NL)
* Denmark (DK)
* Turkey (TR)
* Indonesia (ID)
* Jordan (JO)
* India (IN)
* Cambodia (KH)
* Ethiopia (ET)
* Peru (PE)
* Cuba (CU)
* Argentina (AR)
* Chile (CL)
* Bolivia (BO)
* Spain (ES)
* Bangladesh (BD)
* Pakistan (PK)
* Nigeria (NG)
* Austria (AT)
* Japan (JP)
* Brazil (BR)
* Philippines (PH)
* Vietnam (VN)

# Methods

Requiring the module returns an object containing two root keys:

'countries' and 'provinces'

``` js
var someWhere = require('someWhere')

someWhere.countries; // Returns: [...], An array of countries
someWhere.countries[n]; // Returns: {c : 'Canada', s : 'CA'}, a country object
someWhere.provinces['CA']; // Returns: [{sp: 'AB', p: 'Alberta'},...], an array of province objects

```

# Data Format

Countries cosists of objects containing:

* 'c' : Country name
* 's' : Short country code (eg. CA)

Provinces is an object with country codes as keys, each country code key maps to an object containing:

* 'p' : Province name

[Properties only available in some country keys]
* 'sp' : Abbreviated name
* 'region' : Region name
* 'english' : Name in english

# Install

With [npm](https://npmjs.org) do:

```
npm install someWhere
```

# License

MIT
