
## Deep learning reveals Alzheimer's disease onset in MCI subjects: Results from an international challenge (2018)
> [`paper`](https://www.sciencedirect.com/science/article/pii/S0165027017304296)
### **Dataset**
> - Demographic information (Gender, Age)
> - Cognitive test result (Mini Mental State Examination)
> - Volume/Thickness of  each part in brain  [`dataset`](https://inclass.kaggle.com/c/mci-prediction)
### **Training**
> - 4 class classification (AD/MCI/cMCI/CN)
> - [Method 1] DNN method
>> - Select Feature by feature importance in Random Forest
>> - Learn to selected features by DNN
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/02_model.PNG" width="350"/>

> - [Method 2] Fuzzy method
>> - Define fuzzy set and select features and train Random Forest
>> - Classificaion score average
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/02_model2.PNG" width="500"/>
### **Result**
> - Kaggle result
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/02_result1.PNG" width="400"/>
> - Comparison of different DNN, Fuzzy model result
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/02_result2.PNG" width="500"/>
----
#
#
#
## Deep Structural and Clinical Feature Learning for Semi-Supervised Multiclass Prediction of Alzheimer’s Disease (2018)
> [`paper`](https://ieeexplore.ieee.org/document/8623946)
### **Dataset**
> - Volume/Surface Area/Thickness of each part in brain
> - Cognitive test result
### **Training**
> - 3 class classification (AD/MCI/CN)
> - Pre-train feature by sparse autoencoder
> - Remove output layer and add logistic layer for prediction
> <img src="https://github.com/SSinyu/p/blob/master/img/01_model.PNG" width="700"/>
### **Result**
> - Comparison of different methods
> <img src="https://github.com/SSinyu/p/blob/master/img/01_result1.PNG" width="500"/>
> <img src="https://github.com/SSinyu/p/blob/master/img/01_result2.PNG" width="500"/>
---
#
#
#
## Disease Prediction using Graph Convolutional Networks: Application to Autism Spectrum Disorder and Alzheimer’s Disease (2018)
> [`paper`](https://arxiv.org/pdf/1806.01738.pdf)
### **Dataset**
> - Demographic information (Gender, Age)
> - Genetic information(APOE4)
> - Volume of each part in brain
### **Training**
> - 2 class classificaion (AD/MCI, sMCI/pMCI)
> - Construct graph structure using various methods
> - Learning with Graph ConvNet
> <img src="https://github.com/SSinyu/p/blob/master/img/03_model.PNG" width="800"/>
### **Result**
> - Comparison of different graph structure 
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/03_result2.PNG" width="500"/>

> - Comparison of different classifiers
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/03_result3.PNG" width="550"/>
---
#
#
#
## Multi-class Alzheimer’s disease classification using image and clinical features (2018)
> [`paper`](https://www.sciencedirect.com/science/article/abs/pii/S1746809418300508)
### **Dataset**
> - MRI
> - Clinical data (FAQ, NPI, GDS)
### **Training**
> - 2 class classification (AD/CN, AD/MCI, CN/MCI)
> - Extract multi-modal features
> - Ensemble of SVM, KNN, DT results
> <img src="https://github.com/SSinyu/p/blob/master/img/05_model1.PNG" width="400"/>
### **Result**
> - Comparison of different model
> <img src="https://github.com/SSinyu/p/blob/master/img/05_result1.PNG" width="650"/>
---
#
#
#
## A parameter-efficient deep learning approach to predict conversion from mild cognitive impairment to Alzheimer's disease (2019)
> [`paper`](https://www.biorxiv.org/content/10.1101/383687v3)
### **Dataset**
> - Demographic information (Gender, Age)
> - Genetic information(APOE4)
> - MRI, Extracted local Jacobian Determinant (JD)
> - Cognitive test result (CDRSB, ADAS11, ADAS13, RAVLT)
### **Training**
> - 2 class classificaion (AD/CN, sMCI/pMCI)
> - Extract multi-modal features
> <img src="https://github.com/SSinyu/p/blob/master/img/04_model1.PNG" width="400"/>
### **Result**
> - Comparison of different input modalities
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/04_result1.PNG" width="550"/>
---
