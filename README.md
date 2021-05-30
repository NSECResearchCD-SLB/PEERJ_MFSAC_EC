# PEERJ_MFSAC_EC
Following :--
# LINK TO NOTEBOOK ON COLAB:
https://colab.research.google.com/drive/1GrN0ELvIzU5Tgen0gcSFSaQo2I2AV9gb?usp=sharing
# MFSAC
Multi-Filtering Supervised Attribute Clustering is a method which is designed to be used on Gene Expression Datasets for Filtering as well as Attribute or Gene Augmentation and providing better genes for Cancer Classification.
Please note that here MFSGC AND MFSAC are used interchangeably where an Attribute in a Dataset and Gene in a Gene Expression Dataset are considered synonymous.
## Setup.
The notebooks have been used on Google Colab.If you wish to use a local setup (not recommended), follow these step:- 
1. Install Python 3.8
2. Install Jupyter Notebook.
3. Start Jupyter notebook on your local setup and then open the notebooks.

## Datasets.
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

## Usage
Run the notebooks (here we assume Google Colab). 
1. Run all the cells
2. replace the id with the id of the dataset to be used from the list in the comments
3. verify the email id.
Parameter : 
1. change the value of P to select the no of top genes 
2. In the begining of each part loocv,10 fold and 5 fold . There are two parameters for changing the no of bootstrap versions to create in each iteration and sample no to use.
3. At the end of each part , the corresponding run results , accuracy and various plots will be printed.
