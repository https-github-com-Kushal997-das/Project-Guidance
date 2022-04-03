**Gender Voice Prediction**

**GOAL**

The goal of this project is to predict gender's voice based on the various specific parameters taken into consideration using dataset.


**DATASET**

Dataset can be downloaded from [here](https://www.kaggle.com/datasets/primaryobjects/voicegender).


**WHAT I HAD DONE**

- Step 1: Data Exploratory Analysis
- Step 2: Feature Engineering
- Step 3: Feature Scaling
- Step 4: Data Training & Testing
- Step 5: Modelling 
- Step 6: TP, TN, FP, FN
- Step 7: Auto ML


**MODELS USED**

-  Logistic Regression
-  Random Forest
-  KNN
-  Bagging
-  Gradient Boosting
-  Decision Tree
-  Auto ML


**LIBRARIES NEEDED**

- pandas
- numpy
- matplotlib
- seaborn
- mglearn
- sklearn


**COLUMN DESCRIPTION**

target variable: label (male or female) 20 independent variables:
meanfreq: mean frequency of the voice audio of the person (in kHz)
sd: standard deviation of the frequency of the voice audio
median: median frequency of the voice audio (in kHz)
Q25: first quantile (in kHz)
Q75: third quantile (in kHz)
IQR: interquantile range (in kHz)
skew: Skewness refers to a distortion or asymmetry that deviates from the symmetrical bell curve, or normal distribution
kurt: Kurtosis is a statistical measure that defines how heavily the tails of a distribution differ from the tails of a normal distribution.
sp.ent: spectral entropy
sfm: spectral flatness
mode: mode frequency
centroid: frequency centroid (see specprop)
meanfun: mean fundamental frequency measured across acoustic signal
minfun: minimum fundamental frequency measured across acoustic signal
maxfun: maximum fundamental frequency measured across acoustic signal
meandom: mean of dominant frequency measured across acoustic signal
mindom: minimum of dominant frequency measured across acoustic signal
maxdom: maximum of dominant frequency measured across acoustic signal
dfrange: range of dominant frequency measured across acoustic signal
modindx: modulation index


**CONCLUSION**

Comparing all the accuracies of the models, we could determine that the Random Forest and Support Vector Machine are most efficient models.
