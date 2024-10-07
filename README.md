# Test data for TopoToolbox

If you are looking for the digital elevation models used in TopoToolbox documentation and examples, check out the [TopoToolbox/DEMs](https://github.com/TopoToolbox/DEMs) repository.

This repository provides digital elevation models and derivative products for snapshot testing of TopoToolbox.

Raw data files are not included in the repository but are attached as binary files to releases of the repository. SHA256 checksums of the snapshots are committed to the repository in the file sha256sum.txt and can be used to verify that you have correctly downloaded and extracted the expected versions of the snapshots by running

```
> sha256sum -c sha256sum.txt
```

from a terminal in the directory where you have extracted the data files.

Snapshot datasets are located in subdirectories within this repository. The original digital elevation model should be stored in a file called `dem.tif`. Derivatives of this DEM are created by an automated MATLAB test script in [TopoToolbox/topotoolbox3](https://github.com/TopoToolbox/topotoolbox3) and have names derived from the functions used to create them.
