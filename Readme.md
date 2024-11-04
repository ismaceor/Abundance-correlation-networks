# Data and code for the paper "Analyzing bacterial networks and interations in skin and gills of *Sparus Aurata* with microalgae-based additive feeding"

In this repository you will find the data needed to reproduce the results of the paper. The folder data contains the data on ASV reads for all the samples in all the treatments. The notebook in the code folder exemplifies how to reproduce results for the gills data. For skin the reproduction of results can be done by modifying the input files. In the results folder the results of the community structure analysis are stored.

The community structure was found with the help of the [Radatools software](https://webs-deim.urv.cat/~sergio.gomez/radatools.php) using the following command: 

``>>> command.exe v WS f 1 red.net "communities_.txt" ``

The visual representations of the networks and some basic analysis were done using [Cytoscape](https://cytoscape.org/). 

The diversity analysis was done using a different code in R that is available under request to the authors. 

## Citation

> Cerezo, I.M., Herrada, E.A. , Fernández-Gracia, J., Sáez-Casado, M.I., Martos-Sitcha, J.A., Moriñigo, M.A. and Tapia-Paniagua, S.T. *Analyzing bacterial networks and interations in skin and gills of *Sparus Aurata* with microalgae-based additive feeding.*
