# GEMDAT test data

The test data are from a test discharge saved in HDF5 format.

```python
from imas2xarray import to_xarray

dataset = to_xarray('./data', ids='core_profiles')
```
