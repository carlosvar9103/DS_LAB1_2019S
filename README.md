# DS_LAB1_2019S
Data Stewardship Exercise 1 - Experiment with open data from data.gv.at and data.europa.eu
DOI 10.17605/OSF.IO/RCMZG

The data is collected from governmental sources:

1. Catalog Population according to foreign origin since 2011 Vienna
Name: vie_105.csv
Size: 178 KB
URL: https://www.wien.gv.at/statistik/ogd/vie_105.csv

2. Raw data of Erasmus student mobility (study exchanges and work placements in 2012-13).
Name: SM_2012_13_20141103_01.csv
Size: 44697 KB
URL: http://data.europa.eu/euodp/data/uploads/EAC/SM_2012_13_20141103_01.csv

The experiment runs in a Jupyter notebook using python version 3.7.

Important thing is to install the packeges:

import csv
import numpy as np
import pandas as pd
import plotly
import plotly.plotly as py
import plotly.graph_objs as go
import plotly.tools as tls

To run it is necessary to upload the input data in a folder named "data" with the same names as downloaded from the official sources (This is also provided in the files of the reposotory) IN FORMAT CSV, so it might be uncompressed if it is the case.

You can run all the cells at once or go step by step in the notebook.

The output data is generated directelly in the notebook, if you want to download it this is possible using the options right on top of every graphic embedded in the plotly frame. You can also find the outputs in this repository or with the DOI 10.17605/OSF.IO/D3ZG5
