# Data in HDF5 Format

These folders contain the data in HDF5 format. `refined` contains the 300 cells used in [Paulson et al.](https://www.sciencedirect.com/science/article/pii/S0378775322001495),
and `other` contains any other cell for which we have documentation.

An example of how to read a cell using Argonne's Battery Data Toolkit:

```python
from batdata.data import BatteryDataset
BatteryDataset.from_batdata_hdf('./data/refined/batch_B28B_cell_2.h5')
```
