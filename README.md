# APS MDA file reader

After Pviewer - A Packaged Array Data Viewer Written in Python Language by Ben-chin K Cha & Timothy Mooney and maintained by Ben-chin Cha (cha@aps.anl.gov) [1]. The file is rewritten from readMDA.py, version 4 of Tim Mooney 8/22/02, with the following updates:

* Updated to py3 from py2
* Updated names of certain objects and variables to avoid conflict with the names of system defaults
* Removed interactive GUI and main program
* Renamd readScan to _readScan as an internal method
* Renamd readMDA to _readMDA as an internal method

Usage: load in jupyter notebook.
* To load all methods, use
```
from mdaUtils import _readScan, _readMDA, readMDA
```

* For normal use, use
```
from mdaUtils import *
```

Reference:

[1] https://epics.anl.gov/bcda/dataVis/pviewer.html#HDR1_1
