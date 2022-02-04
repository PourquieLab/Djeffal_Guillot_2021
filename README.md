# Guillot_2021

scRNA-seq data analysis for figures appearing in the following publication:

https://elifesciences.org/articles/64819

Start by cloning this repository using git:
```
git clone https://github.com/pourquielab/Guillot_2021.git
cd Guillot_2021
```
Create a Python 3.8 conda environment to manage the required software packages:

conda create --name py38

Activate the environment:

source activate py38

Begin installing packages with conda and pip:
```
pip install scanpy
pip install jupyterlab
pip install wot
pip install scrublet
pip install bbknn
```

Run the JupyterLab notebooks

Activate the py38 environment and run Jupyter Lab. Within Jupyter lab, navigate to one of the dataset folders and open the .ipynb file.
```
source activate py38
jupyter lab
```
