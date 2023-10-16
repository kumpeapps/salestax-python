# salestax-python
Python module for gathering sales tax rates
Currently only supports Arkansas. Feel free to submit a pull request to help add other states.

```
from salestax import Arkansas as ar

ar.get(street, city, zip)
```