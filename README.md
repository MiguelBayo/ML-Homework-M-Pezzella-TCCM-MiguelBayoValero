# ML-Homework-M-Pezzella-TCCM-MiguelBayoValero
This Github repository contains the python code and corresponding files for the machine learning homework of Marco Pezzella:  Predicting C2H2 and C2 energy level for TCCM.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The first exercise consists in the coding of two ML models for the predicition of the energy levels of C2H2 adding and excluding quantum symmetry numbers. In this case, a deep-learning approach and a random forest programmes have been developed.
"DLR-nosym.py" and "RF-nosym.py" are the python codes corresponding to the deep learning approach and random forest model, respectively. They DO NOT include symmetry quantum numbers.
This code will produce different files:
  1. "c2h2-predictions-DLR.txt", which include the predicition made by the program and the corresponding evaluation metrics to assess the performance of the deep learning model.
  2. "c2h2-predictions-RF.txt",  which include the predicition made by the program and the corresponding evaluation metrics to assess the performance of the random forest model.
"DLR-symm.py" and "RF-symm.py" are the python codes corresponding to the deep learning approach and random forest model, respectively. They DO include symmetry quantum numbers.
This code will produce different files:
  1. "c2h2-predictions-symmetry-dlr.txt", which include the predicition made by the program and the corresponding evaluation metrics to assess the performance of the deep learning model.
  2. "c2h2-clusters-dlr.csv", which include the information about the cluster process and K-Means clusterization such as centroids and plotting information for the deep learning model.
  3. "c2h2-clusters-rf.csv", which include the information about the cluster process and K-Means clusterization such as centroids and plotting information for the random forest model.
Note that all the .csv files, "c2h2-predictions-DLR.txt" and "c2h2-predictions-RF.txt" are given in this repository. However, they are automatically produced by the corresponding codes. Their production can also be deactivated by commenting out the respective printing lines.
"c2h2-energylevels-2019-03-20.txt" is the input file retrieved from the Marvel website. Note that a name has been given to each column for clarity.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The second exercise consists in the study of the rovibrational levels of 12C2 and its isotope 13C2. This exercise includes the prediciton of the diatomic constants of the states X(1SIGMAg+) and b(3SIGMAg-) for both 12C2 and 13C2 with random forest model with linear and polynomial regression (RF/LR and RF/PR). Additionally, the heat capacity and partition function have also been reproduced with a kernel ridge regression (KRR) model.
"12C2-spec-ctes-x.py" and "12C2-spec-ctes-b.py" use RF/LR and RF/PR to predict the rovibrational constants of the states  X(1SIGMAg+) and b(3SIGMAg-) for 12C2, respectively.
"13C2-spec-ctes-x.py" and "13C2-spec-ctes-b.py" use RF/LR and RF/PR to predict the rovibrational constants of the states  X(1SIGMAg+) and b(3SIGMAg-) for 13C2, respectively.
In order to run this codes, the input files "12C2__8states.states" and "13C2__8states.states" retrived from ExoMol website, are used. Note that a name has been given to each column for clarity.
"HC-12C2.py" uses KRR model to predict the heat capacity of 12C2. 
"12C2__8states.cp.txt" is used to run this program. The input is retrived from ExoMol website. Note that a name has been given to each column for clarity.
"PF-12C2.py" uses KRR model to predict the partition function of 12C2. 
"12C2__8states.pf.txt" is used to run this program. The input is retrived from ExoMol website. Note that a name has been given to each column for clarity.
