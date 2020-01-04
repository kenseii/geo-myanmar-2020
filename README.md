# geo workshop

slides and code for the geospatial datascience lecture in myanmar

## Setup
1. create a conda environment and install the requirements
```sh
$ conda env create -f environment.yml
```
2. activate the environment
```sh
$ conda activate myanmar
```
3. install the notebook extensions(you need node and npm)

```sh
$ jupyter nbextension install --py --sys-prefix keplergl # can be skipped for notebook 5.3 and above
$ jupyter nbextension enable --py --sys-prefix keplergl # can be skipped for notebook 5.3 and above
$ jupyter labextension install @jupyter-widgets/jupyterlab-manager keplergl-jupyter
```
4. run the jupyter notebook
```sh
$ jupyter notebook
```