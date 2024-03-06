# PyAiGIS

## AiGIS2/PyAiGIS

AiGIS2/PyAiGIS is an our new project that aims to develop an interactive
analysis and visualization environment for irregular-shaped small body
exploration data on Jupiter Notebook with Python.

As we introduced our preliminary achievements in the following meeting,

     * Nagayoshi and Hirata (2022) AiGIS2, a Jupyter Notebook-based Interactive Analysis and Visualization Tool for Asteroid Exploration Data, AGU Fall Meeting 2022, held in Chicago, IL, 12-16 December 2022, id.[[https://ui.adsabs.harvard.edu/abs/2022AGUFM.P25F2187N/abstract|P25F-2187]].
     * Nagayoshi and Hirata (2023) AiGIS2, Interactive, Versatile Analysis and Visualization Tool for Asteroid Exploration Data, AGU Fall Meeting 2023, P33F-3207.

we will share them through this webpage.

## Technologies

AiGIS2/PyAiGIS is developed with the following technologies:

- [VTK](https://vtk.org)
- [PyVista](https://docs.pyvista.org/version/stable/)
- [PyVistaQt](https://qtdocs.pyvista.org)
- [Pandas](https://pandas.pydata.org)
- [Matplotlib](https://matplotlib.org)
- [Numpy](https://numpy.org)
- [SpiceyPy](https://github.com/AndrewAnnex/SpiceyPy)
- [Jupyter Notebook/Jupyter Lab](https://jupyter.org)

## Screenshots

Examples of visualization of Itokawa shape and associated mapdata by
AiGIS2/PyAiGIS.

Multi-view visualization of Itokawa shape and associated mapdata.

<img src="/aigis2/itokawa_pyvistaqt.png" data-query="?400"
width="400" />

2D distribution plot of the surface slope and elevation of Itokawa
mapdata by Matplotlib.

<img src="/aigis2/Itokawa_SlopeVSElevation.png" data-query="?400"
width="400" />

Smooth terrain on Itokawa (regions where the slope is \< 10 \[deg\] and
the elevation is \< -18 \[m\] are colored).

<img src="/aigis2/Itokawa_PyVista_Selection.png" data-query="?400"
width="400" />

Slope distributions on Itokawa (slope directions and slopes are
visualized with arrows).

<img src="/aigis2/Itokawa_SlopeVectors.png" data-query="?400"
width="400" />

## Contact

Please send your questions and comments to Naru Hirata
(naru@u-aizu.ac.jp) or our group mail address (arcspace@u-aizu.ac.jp).

## Acknowledgements

AiGIS2/PyAiGIS is developed as a research project by students at the
University of Aizu.  
The project is/was supported by:

- ARC-Space, the University of Aizu, Distinctive Joint Research Center
  supported by MEXT Grant Number
  JPMXP0619217839/JPMXP0622717003/JPMXP0723830458.
