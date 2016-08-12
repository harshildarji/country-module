# Country Module    [![Build Status](https://travis-ci.org/H-Darji/country-module.svg?branch=master)](https://travis-ci.org/H-Darji/country-module)
Python module for country codes with ISO codes.

#### How to use?

- Download **`country.py`**.
- Place **`country.py`** into your project folder.
- Import it in your program file as:
```python
import country
```
- Now, to get country code:
```python
country.see[cName][0]   # cName = country name, 0 to get country code
```
- To get country ISO code:
```python
country.see[cName][1]   # cName = country name, 1 to get ISO code
```

#### Example:

```python
import country

while True:
    cName = input('Country: ').title()
    print('Country code of %s: %s' % (cName, country.see[cName][0]))
    print('ISO code of %s: %s\n' % (cName, country.see[cName][1]))
```
