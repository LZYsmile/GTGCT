# GTGCT
Summary for Stack Overflow from Mined Code Snippets via Graph Transformer
## 1.Environment Setup
The code is tested with Python 3.6. All dependencies are listed in [requirements.txt](https://github.com/LZYsmile/Summary-for-Stack-Overflow-from-Mined-Code-Snippets-via-Graph-Transformer/blob/master/requirements.txt).
## 2.Dataset
We use csharp, Java, javascript, python, SQL five data sets to evaluate our model. These data sets are from the Code2Que article. Relevant references are given in our paper
## 3.Model Training and Testing
If you want to use our model quickly, first you need to place trans.py and evaluation.py in the same folder. Create a Save folder in this folder to hold the model. Create fold_1 folder to hold the dataset. In fold_1, create folders for train, test, and dev respectively, and place the data sets that need to be run in the corresponding folders. Run trans.py to train the model and generate the predicted R.TXT file and reference file. Run evaluation.py to calculate the score
