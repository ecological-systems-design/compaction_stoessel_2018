# Assessing the environmental impacts of soil compaction in Life Cycle Assessment

This code is related to the publication "Assessing the environmental impacts of soil compaction in Life Cycle Assessment" by Stoessel et al. (2018), available at https://www.sciencedirect.com/science/article/pii/S0048969718306211.

The output as well as an prepared input file for the soil clay content can be found at https://doi.org/10.3929/ethz-b-000253177.

The code is written to use the provided folder structure.  
Data should be downloaded and saved accordingly (see 4).  
People familiar with python environments may use the `py36_gis.yml` or the `requirements.txt` file.  
Others may follow the instructions below.


### CONTENT

1. Installing Python
2. Creating Conda environment
3. Starting Jupyter Notebook and run the code
4. Data Download

### 1) Installing Python

Python has been installed with the Miniconda installer:
http://conda.pydata.org/miniconda.html
- conda version: 4.3.22
- python version: 3.5.2.final.0
- requests version: 2.12.4

### 2) Creating Conda environment

The virtual environment used for all the calculations has been set up the following way:

Create environment with Python 3.6:

- `conda create -n 'environment_name' python=3.6`


Activate environment:

- `(source) activate 'environment_name'`

Install packages:

from conda-forge channel (`conda install -c conda-forge 'package'`):

- rasterstats
- geopandas
- netcdf4

from conda (`conda install 'package'`):

- (nb_conda_kernels (in root environment, i.e. without having the environment activated))	
- (ipykernel (to make nb_conda_kernels work))
- xlrd
- openpyxl

These packages should have come with the ones above:
- numpy
- scipy
- matplotlib
- pandas

### 3) Starting Jupyter Notebook and run the code

- type `jupyter notebook` in your command line
- head to the folder with the code (or do this in the command line before typing "jupyter notebook")
- run notebooks in order of numbering

### 4) Data download

download data from the sources provided in the first notebook into the folder structure
