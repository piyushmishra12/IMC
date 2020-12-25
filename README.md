# IMC_Gene


## This is the readme file that contains the guidelines and information about the compilation of the code of the following paper

**Paper Name:-** [Incomplete Multi-view Gene Clustering with Data Regeneration using Shape Boltzmann Machine]() 

- **Authors:** Pratik Dutta<sup>1</sup>, Piyush Mishra<sup>2</sup> and Sriparna Saha<sup>1</sup>.
- **Affiliation:** <sup>1</sup>Department of Computer Science and Engineering, Indian Institute of Technology Patna; <sup>2</sup>Department of Computer Science and Engineering, IIIT Bhubaneswar.  
- **Accepted:(08/08/2020):** [Computers in Medicine and Biology, Elsevier](https://www.sciencedirect.com/science/article/abs/pii/S0010482520302985)

The paper presents a pipeline of methodology which seeks to remove the previous redundancies and unnecessary complications in computations for such kind of experimentation in multi-view gene clustering. For the most part, the study is successful in providing it with easy to understand code. A huge effort is put to make sure code is not a barrier to understanding the nuances of the study.

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
