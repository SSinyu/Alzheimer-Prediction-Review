# Alzheimer Prediction Review

---

## 01. Deep Structural and Clinical Feature Learning for Semi-Supervised Multiclass Prediction of Alzheimer’s Disease (2018)  
https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8623946\
### **Dataset**  
> -	volume, surface area, cortical thickness, cognitive test features.
### **Training**  
> -	Sparse Autoencoder based feature learning  
> -	pretrained weight + logistic layer  
> ![01_model](https://github.com/SSinyu/p/blob/master/img/01_model.PNG)  
### **Result**  
> -	SVM-based methods  
> <img src="https://github.com/SSinyu/p/blob/master/img/01_result1.PNG" width="550"/>  
> -	Deep learning methods  
> <img src="https://github.com/SSinyu/p/blob/master/img/01_result2.PNG" width="550"/>  

---
#
#
#
## 02. Deep learning reveals Alzheimer's disease onset in MCI subjects: Results from an international challenge (2018)  
https://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S0165027017304296\
### **Dataset**  
> -	volumes, thickness (https://inclass.kaggle.com/c/mci-prediction/data\)  
### **Training**  
> -	select features by Random Forest  
> -	DNN training  
> <img src="https://github.com/SSinyu/p/blob/master/img/02_model.PNG" width="400"/>  

### **Result**  

> <img src="https://github.com/SSinyu/p/blob/master/img/02_result1.PNG" width="550"/>  

> <img src="https://github.com/SSinyu/p/blob/master/img/02_result2.PNG" width="550"/>  

---
#
#
#
## 03. Disease Prediction using Graph Convolutional Networks: Application to Autism Spectrum Disorder and Alzheimer’s Disease (2018)  
https://arxiv.org/pdf/1806.01738.pdf\
### **INPUT**  
> -	use the volumes of all C = 138 segmented brain structures  
> -	+graph information (age, sex, genetic info)  
### **TRAINING**  
> -	Graph Convolutional networks  
> ![03_model](https://github.com/SSinyu/p/blob/master/img/03_model.PNG)  
### **RESULT**  

> -	Influence of polynomial order  

> <img src="https://github.com/SSinyu/p/blob/master/img/03_result1.PNG" width="550"/>  

> -	Influence of phenotypic measures  

> <img src="https://github.com/SSinyu/p/blob/master/img/03_result2.PNG" width="550"/>  

---
#
#
#
## 04. A parameter-efficient deep learning approach to predict conversion from mild cognitive impairment to Alzheimer's disease (2019)  
https://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S105381191930031X
### **INPUT**  
> - MRI, extracted local Jacobian Determinant(JD) image, tabular clinical data (Multimodal)  
### **TRAINING**  
> - Feature extractor layer are shared two task  
> - predict two tasks (AD/HC, pMCI/sMCI)  
> <img src="https://github.com/SSinyu/p/blob/master/img/04_model.PNG" width="300"/>  

### **RESULT**  
> - ::  

---
#
#
#
## 05. A deep learning model for early prediction of Alzheimer's disease dementia based on hippocampal MRI (2019)  
https://arxiv.org/ftp/arxiv/papers/1904/1904.07282.pdf
### **INPUT**  
> - (left/right) Hippocampus extracted from T1 MRI  
### **TRAINING**  
> ![05_model](https://github.com/SSinyu/p/blob/master/img/05_model.PNG)  
### **RESULT**  
> - map  
> ![05_result](https://github.com/SSinyu/p/blob/master/img/05_result.PNG)  

---
#
#
#
## 06. Hippocampus Analysis by Combination of 3D DenseNet and Shapes for Alzheimer’s Disease Diagnosis (2018)  
> https://sci-hub.tw/10.1109/jbhi.2018.2882392
### **INPUT**  
> - (left/right) Hippocampus segmentation and 3D patch extraction  
### **TRAINING**  
> - overview  
> ![06_model1](https://github.com/SSinyu/p/blob/master/img/06_model1.PNG)  
> - 3D DenseNet : learn visual features  
> ![06_model2](https://github.com/SSinyu/p/blob/master/img/06_model2.PNG)  
> - Hippocampal Shape Analysis : extract shape features  
> ![06_model3](https://github.com/SSinyu/p/blob/master/img/06_model3.PNG)  
> ### **RESULT**  
> - comparison of different patch size  
> ![06_result1](https://github.com/SSinyu/p/blob/master/img/06_result1.PNG)  
> - comparison of different model  
> ![06_result2](https://github.com/SSinyu/p/blob/master/img/06_result2.PNG)  
> - comparison of different methods  
> ![06_result3](https://github.com/SSinyu/p/blob/master/img/06_result3.PNG)  

---
#
#
#
## 07. Alzheimer's disease diagnosis based on multiple cluster dense convolutional networks (2018)  
https://sci-hub.tw/https://www.sciencedirect.com/science/article/abs/pii/S089561111830199X
### **INPUT**  
> - 3D patches from T1 MRI  
### **TRAINING**  
> 1. find the groups of patches by K-means clustering (32x32x32 size)  
> 2. reduce feature dimension by PCA (2000 dim)  
> 3. use Multi-clsuter DenseNet  
> ![07_model](https://github.com/SSinyu/p/blob/master/img/07_model.PNG)  
### **RESULT**  
> - comparison of different K  
> ![07_result1](https://github.com/SSinyu/p/blob/master/img/07_result1.PNG)  
> - comparison of different model  
> ![07_result2](https://github.com/SSinyu/p/blob/master/img/07_result2.PNG)  


---
#
#
#
Tabular data application
========================

---
#
#
#
## 01. SuperTML: Two-Dimensional Word Embedding for the Precognition on Structured Tabular Data (2019)
https://arxiv.org/pdf/1903.06246v3.pdf\
### **TRAINING**
> -	images with two-dim embeddings of the features in tabular data 
> ![_01_data1](https://github.com/SSinyu/p/blob/master/img/_01_data1.PNG) 
> ![_01_data2](https://github.com/SSinyu/p/blob/master/img/_01_data2.PNG)
> -	fine-tuning the pretrained CNN model.
### **RESULT**
> ![_01_result1](https://github.com/SSinyu/p/blob/master/img/_01_result1.PNG) 
> ![_01_result2](https://github.com/SSinyu/p/blob/master/img/_01_result2.PNG)

---
#
#
#
## 02. Regularization Learning Networks: Deep Learning for Tabular Datasets (2018)
https://arxiv.org/pdf/1805.06440v3.pdf

---
