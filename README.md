# Country Module
[![Total alerts](https://img.shields.io/lgtm/alerts/g/harshildarji/country-module.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/harshildarji/country-module/alerts/)

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
country.see[country_name][0]   # pass '0' to get country code
```
- To get country ISO code:
```python
country.see[country_name][1]   # pass '1' to get ISO code
```

#### Example:

```python
import country

while True:
    cName = input('Country: ').title()
    print('Country code of %s: %s' % (cName, country.see[cName][0]))
    print('ISO code of %s: %s\n' % (cName, country.see[cName][1]))
```
