# publication1
This repository contains a dataset and jupyter notebooks used in the work with the PhD thesis of Christian Dalheim Øien.

The standardized version of the 2021 production data (D0) is given in `df_2021.pkl`. The PCA-transformed version with 50 input variables (D1) and the extended version of D1 using lag features (D2) are created in `01 Data processing.ipynb`. The other notebooks train and test models of each algorithm type based on both D1 and D2.

The code for hyperparameter search using GridSearchCV is included in the respective notebooks, but note that it will take several hours to run on a typical laptop or office computer.