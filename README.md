# geo workshop

slides and code for the geospatial datascience lecture in myanmar

## Setup
1. create a conda environment
2. install the requirements
3. install the notebook extensions(you need node and npm)
    $ jupyter nbextension install --py --sys-prefix keplergl # can be skipped for notebook 5.3 and above
    $ jupyter nbextension enable --py --sys-prefix keplergl # can be skipped for notebook 5.3 and above
    $ jupyter labextension install @jupyter-widgets/jupyterlab-manager keplergl-jupyter
