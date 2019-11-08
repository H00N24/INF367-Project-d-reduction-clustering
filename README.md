## INF367 Project 2

Dimensionality reduction & clustering

### Solution
Project assigment and are in `Project 2.ipynb` jupyter notebook.

### Prerequisities
* python >=3.7
* python venv/virtualenv package
* python libraries specified in `requiriments.txt`

### Commands for installing & running the notebook
* Creating and activating python virtual enviroment
```sh
$ python -m virtualenv venv # python -m venv venv
$ source venv/bin/activate
```
* Installing python libraries and ipykernel for jupyter notebook
```sh
[venv]$ pip install -r requiriments-pre.txt # Cython
[venv]$ pip install -r requiriments.txt
[venv]$ python -m ipykernel install --user --name inf367-project-2 --display-name "INF367 Project 2"
```
* Unziping data and running the notebook
```sh
[venv]$ unzip cell_data.zip
[venv]$ jupyter notebook
```
