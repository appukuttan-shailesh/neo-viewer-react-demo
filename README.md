# Neural Activity Visualizer - ReactJS Demo App

This app demonstrates a sample usage of the ReactJS implementation of the `neural-activity-visualizer-react` component.

`neural-activity-visualizer-react` is a JavaScript component for visualizing neural activity data 
(analog signals, spike trains etc.) stored in any of the file formats supported by the 
[Neo](http://neuralensemble.org/neo) library. Implementations are available in 
both AngularJS and ReactJS.

ReactJS Demo App:
https://neo-viewer.brainsimulation.eu/react

`neural-activity-visualizer-react` Homepage:
https://neo-viewer.brainsimulation.eu/

## Quick overview

The component was developed to produce graphical representations of neural activity data based on the Neo object model. [Neo](http://neuralensemble.org/neo) is an open source API implemented in Python supporting many file formats, including several proprietary formats (e.g. AlphaOmega, Plexon, NeuroExplorer), open formats (e.g. Neurodata Without Borders, Klustakwik, Elan) and generic file formats (e.g. MATLAB, ASCII, HDF5). Neo loads this data into a common object model with the aim of increasing interoperability of various software tools used in electrophysiology and thus facilitating sharing of data between different projects. Neo's focus is solely on the structure of the data, with separate tools being required for their analysis. Our compoment comes in at this stage by enabling interactive visualization of data. It makes use of the open source [Plotly](https://plotly.com/javascript/) library for visualisation, owing to its efficiency in handling large data, and [Django](https://www.djangoproject.com/) Python web framework for the backend.


<div><img src="eu_logo.jpg" alt="EU Logo" width="15%" align="right"></div>


## Acknowledgements
This open source software code was developed in part or in whole in the Human Brain Project, funded from the European Union's Horizon 2020 Framework Programme for Research and Innovation under Specific Grant Agreements No. 720270, No. 785907 and No. 945539 (Human Brain Project SGA1, SGA2 and SGA3).
