# IMC_Gene


## This is the readme file that contains the guidelines and information about the compilation the code of the following paper

**Paper Name:-** Incomplete Multi-view Gene Clustering with Data Regeneration using Shape Boltzmann Machine

 ## Getting Started 
 These instructions will allow you to emulate the results obtained from the code for development and testing purposes.
 ### Prerequisites
* **[Python 3.6](https://www.python.org/downloads/)**
* **[sklearn](https://scikit-learn.org/stable/install.html)**
* **[matplotlib 2.0+](https://matplotlib.org/users/installing.html)**
* **[mpl_toolkits](https://matplotlib.org/2.0.2/mpl_toolkits/index.html)**
* **[numpy 1.10+](https://pypi.org/project/numpy/)**
* **[pandas](https://pypi.org/project/pandas/)**
* **[pypdb](https://pypi.org/project/pypdb/)**

### Description

* `clean_seq_and_exp.ipynb` cleans and stores gene sequence and expression data as csv.

* `get_pdb.ipynb` gets the PDB ID data and stores in csv format. Also subsamples from the gene sequence and expression data.

* `encode.ipynb` encodes the data and converts to matrices (images) for easier handling.

* `resize.ipynb` resizes the images.

* `generate.ipynb` generates a common subspace for all the modalities using SBM.

* `clustering.ipynb` performs k-means clustering with the generated data and gives relevant results

* `individual_clustering.ipynb` gives the metrics of clustering performed in individual modalities.

## Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Also you can contact to the corresponding authors [Piyush Mishra](mailto:piyushmishra1999@gmail.com) and [Pratik Dutta](mailto:pratik.pcs16@iitp.ac.in).
