# Dissertation-Achmed-Mrestani-Python-Code

Copy all files of this repository to one folder. 
Download Aanaconda (https://www.anaconda.com/distribution/#download-section).

Move mrestani_diss.yml to the working directory of Anaconda. 
Open Anaconda prompt and create new environment from yml file.
```
conda env create -f mrestani_diss.yml
```
Activate new environment.
```
conda activate mrestani_diss
```
Start jupyter notebook from Anaconda prompt.
Navigate to and open dissertation_achmed_mrestani_notebook.ipynb.
Follow the instructions in the notebook to analyze the test file dStorm647_Nc82_8.txt.
Open dissertation_achmed_mrestani_notebook.html for an already executed version of the notebook.

If this does not work try to install the packages manually.
Open Anaconda prompt and create new environment.
```
conda create --name mrestani_diss
```
Activate new environment.
```
conda activate mrestani_diss
```
Install some more dependencies
```
conda config --add channels conda-forge
conda install cgal jupyter scikit-learn scikit-image hdbscan pandas statsmodels astropy
conda install joblib==0.17.0
```

