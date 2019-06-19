
## FuseMe: Classification of sMRI images by fusion of Deep CNNs in 2D+ ϵ projections (2017)
> [`paper`](https://hal.archives-ouvertes.fr/hal-01674952)
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN, MCI/CN, AD/MCI)
> - Fusion operation on each network (Sagittal/Coronal/Axial)
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/01_model1.PNG" width="800"/>  
### **Result**  
> - Comparison of different fusion result
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/01_result1.PNG"/>
---
#
#
#
## Classification of sMRI for AD Diagnosis with Convolutional Neuronal Networks: A Pilot 2D+ ϵ Study on ADNI (2017)
> [`paper`](https://dl.acm.org/citation.cfm?id=3079010)
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN, MCI/CN, AD/MCI)
> - Extract patches from hippocampus ROI
> - Data Augmentation (flipping, affine transform, blurring)
> - Balancing data (reduce over-sampled category, random duplicate under-sampled category, reduce augmented data)
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/02_model1.PNG" width="650"/>
### **Result**  
> - Comparison of different balancing result
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/02_result1.PNG" width="500"/>

> - Comparison of different arugmentation result
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/02_result2.PNG" width="400"/>
---
#
#
#
## Classification of Alzheimer disease on imaging modalities with deep CNNs using cross-modal transfer learning (2018)
> [`paper`](https://ieeexplore.ieee.org/document/8417262/)
### **Dataset**
> - MRI, MD-DTI
### **Training**
> - 2 class classification (AD/CN, MCI/CN, AD/MCI)
> - Extract patches from hippocampus ROI
> - Data Augmentation (flip, zoom, shift, scale, contrast, noise ...)
> - Fine-tuning pre-trained networks from MRI
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/03_model1.PNG" width="700"/>
### **Result**  
> - Comparison of different method
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/03_result1.PNG"/>
---
#
#
#
## Convolutional neural networks-Based MRI image analysis for the Alzheimer’s disease prediction from mild cognitive impairment (2018)
> [`paper`](https://www.frontiersin.org/articles/10.3389/fnins.2018.00777/full)
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN)
> - Extract 2.5D patches for CNN training
> - Obtain the CNN-based and FreeSurfer-based image features
> - Select each features by PCA and Lasso
> - Combine two features and feed to [`extreme learning machine`](https://ieeexplore.ieee.org/document/6035797) classifier
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/Lin2018_model1.PNG" width="600"/>

> - used CNN
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/Lin2018_model2.PNG" width="700"/>
### **Result**
> - Comparison of different feature used 
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/Lin2018_result1.PNG" width="800"/>

> - Comparison of extreme learning machine with other method
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/ROI_based_CNN/Lin2018_result2.PNG" width="800"/>
---
