
## CNNs based multi-modality classification for AD diagnosis (2017)  
> [`paper`](https://ieeexplore.ieee.org/document/8302281/)  
### **Dataset**
> - MRI, PET
### **Training**
> - 2 class classification (AD/CN)
> - Extract feature with 3D ConvNet
> - Combined feature vector of MRI and PET
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_model1.PNG" width="450"/>  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_model2.PNG" width="600"/>
### **Result**  
> - Comparison of different method
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_result1.PNG"/>  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_result2.PNG"/>
---
#
#
#
## Residual and plain convolutional neural networks for 3D brain MRI classification (2017)
> [`paper`](https://arxiv.org/abs/1701.06643)
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN, AD/EMCI, AD/LMCI, LMCI/EMCI, LMCI/CN, EMCI/CN)
> - Use common ConvNet, ResNet
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Korolev2017_model1.PNG"> 
### **Result**
> - Comparison of different target
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Korolev2017_result1.PNG"/>

> - Visualization of importance areas based on [`paper`](https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf)
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Korolev2017_result2.PNG"/>
---
#
#
#
## Alzheimer's disease classification based on combination of multi-model convolutional network (2017)
> [`paper`](https://ieeexplore.ieee.org/document/8261566)
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN)
> - Learn feature by 3D-CNN, 3D-ConvAutoencoder
> - Combine each features
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/02_model1.PNG" width="700"/>  

> - 3D Conv Autoencoder
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/02_model2.PNG" width="500"/>
### **Result**  
> - Comparison of different method
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/02_result1.PNG"/>
---
#
#
#
## Multimodal learning using convolution neural network and Sparse Autoencoder (2017)
> [`paper`](https://ieeexplore.ieee.org/document/7881683)
### **Dataset**
> - MRI, PET
### **Training**
> - 2 class classification (AD/CN, MCI/CN)
> - Extract 3D patches from MRI, PET
> - Pre-training each input feauture by sparse autoencoder
> - Learn by parameter shared CNN
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Vu2017_model1.PNG"> 
### **Result**
> - Comparison of proposed strategies 
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Vu2017_result1.PNG"/>

> - Comparison of different methods
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Vu2017_result2.PNG"/>
---
#
#
#
## Predicting Conversion of Mild Cognitive Impairments to Alzheimer’s Disease and Exploring Impact of Neuroimaging (2018)
> [`paper`](https://arxiv.org/pdf/1807.11228.pdf)
### **Dataset**
> - MRI, clinical dataset(demographics, cognitive test data, biospecimen data)
### **Training**
> - 2 class classification (sMCI/pMCI)
> - Feature extract from ResNet3D + Histogram loss
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/04_model1.PNG" width="700"/>
### **Result**  
> - Comparison of different method
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/04_result1.PNG" width="500"/>
---
#
#
#
## Deep fusion pipeline for mild cognitive impairment diagnosis (2018)
> [`paper`](https://ieeexplore.ieee.org/document/8363832)
### **Dataset**
> - MRI, Neuropsychological Measures(NM)
### **Training**
> - 2 class classification (AD/CN, MCI/CN, AD/MCI)
> - Learning MRI features by dilated conv, residual/dense connections
> - Combine learned MRI features and NM features
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Senanayake2018_model1.PNG" width="300"/>
### **Result**
> - Comparison of fusion/non-fusion
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Senanayake2018_result1.PNG" width="400"/>
#
#
#
## An efficient 3D deep convolutional network for Alzheimer's disease diagnosis using MR images (2018)
> [`paper`](https://ieeexplore.ieee.org/document/8363543/)
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN)
> - Learning features by 3DConvNet
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Backstrom2018_model1.PNG" width="400"/>

> - Network details
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Backstrom2018_model2.PNG" width="600"/>
### **Result**
> - Comparison of different method
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Backstrom2018_result1.PNG" width="600"/>
---
#
#
#
## Alzheimer’s disease diagnostics by a 3D deeply supervised adaptable convolutional network (2018)
> [`paper`](https://www.ncbi.nlm.nih.gov/pubmed/28930562)
### **Dataset**
> - MRI
### **Training**
> - 2,3 class classification (AD/CN, AD/MCI, MCI/CN, AD/MCI/CN)
> - Extract feature by 3D Conv autoencoder
> - Add fully-connected layer and fine-tuning
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Hosseini2018_model2.PNG" width="750"/>

> - 3D Conv autoencoder
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Hosseini2018_model1.PNG" width="600"/>
### **Result**
> - Performance of the proposed classifier
> - PPV=TP/TP+FP, NPV=TN/TN+FN, BAC=0.5*(SEN+SPE)
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_subject_level_CNN/Hosseini2018_result1.PNG" width="800"/>
---
#
#
#
## Non-white matter tissue extraction and deep convolutional neural network for Alzheimer’s disease detection (2018)
> [`paper`](https://link.springer.com/article/10.1007/s00500-018-3421-5)
> - -
---
#
#
#
## Automated classification of Alzheimer's disease and mild cognitive impairment using a single MRI and deep neural networks (2019)
> [`paper`](https://www.sciencedirect.com/science/article/pii/S2213158218303930?via%3Dihub)
> - -
---
#
#
#
## Ensemble of 3D densely connected convolutional network for diagnosis of mild cognitive impairment and Alzheimer’s disease (2019)
> [`paper`](https://www.sciencedirect.com/science/article/pii/S0925231218314723)
> - -
---
