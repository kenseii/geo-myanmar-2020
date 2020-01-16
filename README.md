# geo workshop

slides and code for the geospatial datascience lecture in myanmar

## Setup
0. if you dont have the Rtree installed please install it this way.
```sh
$ sudo apt install python3-rtree
```

1. create an environment and install the requirements
```sh
$ python3 -m venv myanmar_geo
```
2. activate the environment
```sh
$ source myanmar_geo/bin/activate
```
3. install requirements
```sh
$ pip install -r requirements.txt
```
4. install the notebook extensions(you need node and npm)

```sh
$ jupyter nbextension install --py --sys-prefix keplergl # can be skipped for notebook 5.3 and above
$ jupyter nbextension enable --py --sys-prefix keplergl # can be skipped for notebook 5.3 and above
$ jupyter labextension install @jupyter-widgets/jupyterlab-manager keplergl-jupyter
```
5. run the jupyter notebook
```sh
$ jupyter notebook
```

Note: you may need to update jupyter related libraries like jupyter-console...
```sh
$ pip install --upgrade --force-reinstall jupyter-console
```
