# Afghanistan_PyOnSSET
Python implementation of the OpeN Source Spatial Electrification Toolkit (ONSSET) for Afghanistan.

# Important information prior running the model

The electrification analysis with OnSSET draws the information necessary for the model to work from two supplementary csv files.

The first file containing most of the sensitivity parameters of the analysis (total population, urban population ratio, diesel price etc.) is by convention "specs" and you can find it usually within the db file serving as directory.

The second file contains all the GIS information (21 columns) for the settlements to be included in the analysis. This csv file has by convention the same name with the country it represents (e.g. in this case Afghanistan). When prepared, this file shall be placed within the bd file as well.

A simplified - online -  version of the Afghan OnSSET model is available here: http://35.163.178.100:8891/login?next=%2Ftree