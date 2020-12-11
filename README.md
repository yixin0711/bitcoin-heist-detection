# Detection of Bitcoin Ransomware Address

### Author: Xin Yi and Yiming Tong

This repo hosts python code for data analysis and detection framework of Bitcoin ransom addresses. Dataset is availabel on [UCI Machine Learning Repository
](https://archive.ics.uci.edu/ml/datasets/BitcoinHeistRansomwareAddressDataset). 


[Preliminary Analysis.ipynb](https://github.com/yixin0711/bitcoin-heist-detection/blob/main/Preliminary%20Analysis.ipynb) is for basic exploratory data analysis and generating plots.
[Pycaret Classification.ipynb](https://github.com/yixin0711/bitcoin-heist-detection/blob/main/Pycaret%20Classification.ipynb) contains a API that runs all classification model as our benchmark for heuristics approach.
[Naive Similarity Search.ipynb](https://github.com/yixin0711/bitcoin-heist-detection/blob/main/Naive%20Similarity%20Search.ipynb) contains the caluclation engine for computing Mahalabonis distance and counts of new emerging ransomware addresses.
[Discriminant Analysis.ipynb](https://github.com/yixin0711/bitcoin-heist-detection/blob/main/Discriminant%20Analysis.ipynb) is for performing discriminant analysis of ransom addresses detection.
