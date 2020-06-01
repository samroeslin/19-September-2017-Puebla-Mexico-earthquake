# Seismic recording
The raw seismic recordings for the 2017 Puebla earthquake can be accessed at [CIRES Busqueda de registros](http://www.cires.org.mx/registro_es.php).
The seismic recordings were processed in Matlab and [SeismoSignal](https://seismosoft.com/product/seismosignal/).

# Response spectra
The recorded data was processed in Matlab.
Python code for the processing of seismic recordings can be found at [gmpe-smtk/smtk/response_spectrum.py](https://github.com/GEMScienceTools/gmpe-smtk/blob/master/smtk/response_spectrum.py)

The pseudo-acceleration for the [CIRES (Centro de Instrumentacion y REgistros Sismico, a. c.)](http://www.cires.org.mx/) stations (North-South and East-West directions) are in the folder CIRES data.

The jupyter notebook **[Spectrum 2017 Puebla Mexico earthquake.ipynb]**(https://github.com/sroe459/2017-Puebla-Mexico-earthquake/blob/master/Spectrum%202017%20Puebla%20Mexico%20earthquake.ipynb) includes the code for plotting the spectrum. It uses [plotly](https://plotly.com/python/) to get intearctive graphs. The notebook can be displayed using [jupyternbviewer](https://nbviewer.jupyter.org/).
