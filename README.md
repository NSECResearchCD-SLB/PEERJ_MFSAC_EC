# PEERJ_MFSAC_EC
Following :--
# LINK TO NOTEBOOK ON COLAB:
https://colab.research.google.com/drive/1GrN0ELvIzU5Tgen0gcSFSaQo2I2AV9gb?usp=sharing
# MFSAC
Multi-Filtering Supervised Attribute Clustering is a method which is designed to be used on Gene Expression Datasets for Filtering as well as Attribute or Gene Augmentation and providing better genes for Cancer Classification.
Please note that here MFSGC AND MFSAC are used interchangeably where an Attribute in a Dataset and Gene in a Gene Expression Dataset are considered synonymous.
# Setup
The notebooks have been used on Google Colab.

https://colab.research.google.com/drive/1GrN0ELvIzU5Tgen0gcSFSaQo2I2AV9gb?usp=sharing

### Alternatively
If you wish to use a local setup (not recommended), follow these step:- 
1. Install Python 3.8
2. Install Jupyter Notebook.
3. Start Jupyter notebook on your local setup and then open the notebooks.

# Datasets.
The datasets used for our proposed methods are:-
1. Leukemia 
2. Colon 
3. Prostate 
4. Lung 
5. RBreast
6. Breast 
7. MLL 
8. SRBCT
9. RAHC
10. RAOA

The dasets are provided in the CANCER GENE EXPRESSION DATASETS directory under this repository .

https://github.com/NSECResearchCD-SLB/PEERJ_MFSAC_EC/tree/main/CANCER%20GENE%20EXPRESSION%20DATASETS

Each of the dataset has an .csv extention but are seperated by \t or TAB delimiter .
The datasets are in form of TAB seperated matrices and can be imported in python by 
```python
import pandas as pd
dataset=pd.read_csv("name_of_data.csv",sep="\t",header=None)
```
# Usage
Run the notebooks (here we assume Google Colab). 
1. Run all the cells
2. verify the google email ID . in the first block of Loading the Dataset outupt section.
Parameter : 
1. change the value of P_VALUE , BOOT_VALUE , SAMPLE_VALUE as required and replace the dataset IDs. In the first block of Load the Dataset section
3. At the end of each part , the corresponding run results , accuracy and various plots will be printed.
