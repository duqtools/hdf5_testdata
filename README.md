# GEMDAT test data

The test data are from a test discharge saved in HDF5 format.

```python
from imas2xarray import to_xarray

dataset = to_xarray('./data', ids='core_profiles')
```

## Download

1. using git: `git clone https://github.com/duqtools/hdf5_testdata.git`
2. [direct link to data](http://github.com/duqtools/hdf5_testdata/zipball/main/)
