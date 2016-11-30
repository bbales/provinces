# provinces

state and province lists for countries

# Completeness

This module currently has states and provinces for:

* united states (US)
* united kingdom (GB)
* canada (CA)
* mexico (MX)
* australia (AU)
* china (CN)
* germany (DE)
* belgium (BE)
* netherlands (NL)
* denmark (DK)
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
* Japan (JP)
* austria (AT)
* brazil (BR)
* Philippines (PH)
* Vietnam (VN)

# Methods

``` js
var provinces = require('provinces')
```

Requiring the module returns an object containing two root keys:

'countries' and 'provinces'

Although 'provinces' is a misnomer for much of the data in this module, it was used to generalize regions, states, provinces etc.

# Data Format

Countries cosists of objects containing:

* 'c' : Country name
* 's' : Short country code (eg. CA)

Provinces is an object with country codes as keys, each country code key maps to an object containing:

(- designates that this property is only available in some country key objects)

* 'p' : Province name
- 'sp' : Abbreviated name
- 'region' : Region name
- 'english' : Name in english

# Install

<!-- With [npm](https://npmjs.org) do: -->

```
npm install provinces
```

# License

MIT
