# StackDPPred: Multiclass Prediction of Defensin Peptides using Stacked Ensemble Learning with Optimized Features

##Pipeline
##StackDPPred uses the following dependencies:
Python 3.8
numpy
scipy
scikit-learn
pandas
matplotlib
MATLAB (R2018a)

**The Dataset folder contains DPs dataset in fasta.

**Feature extraction: SAAC.m is the implementation of splite amino acid compositon .FEGS is the implementation of feature extraction based graphical and statistical method. SegPSSM contains the segmented position specific scoring matrix features, HOG.m is the implementation of  histogram of oriented gradients-based PSSM method.

** Classifier: This directory contain the MLP, Catboost, GNB,DT and Stack etc, ML classifiers implementation to predict DPs functional types.
