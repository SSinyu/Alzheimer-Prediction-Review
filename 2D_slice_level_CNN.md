
## 01. A deep CNN based multi-class classification of Alzheimer's disease using MRI (2017)
https://sci-hub.tw/10.1109/ist.2017.8261460
### **Dataset**
> - MRI
### **Training**
> - 4 class classification (AD/LMCI/EMCI/CN)
> - GoogLeNet, ResNet-18, ResNet-152  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/01_model1.PNG" width="200"/>
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/01_model2.PNG" width="200"/>  
### **Result**
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/01_result1.PNG" width="700"/>
----
#
#
#
## 02. Applying convolutional neural networks for pre-detection of alzheimer's disease from structural MRI data (2017)
https://sci-hub.tw/10.1109/m2vip.2017.8211486
### **Dataset**
> - MRI
### **Training**
> - 3 class classification (AD/EMCI/CN)
> - SVM, Custom ConvNet  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/02_model1.PNG" width="500"/>  
### **Result**  
> -
---
#
#
#
## 03. Towards Alzheimer's disease classification through transfer learning (2017)
https://sci-hub.tw/10.1109/bibm.2017.8217822
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN)
> - Fine-tuning pre-trained VGG16 / Inception-V4 from ImageNet
### **Result**  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/03_result1.PNG"/>
---
#
#
#
## 04. Deep Residual Nets for Improved Alzheimer's Diagnosis (2017)
https://sci-hub.tw/10.1145/3107411.3108224
### **Dataset**
> - MRI
### **Training**
> - 3 class classification (AD/MCI/CN)
> - Fine-tuning pre-trained ResNet  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/04_model1.PNG" width="500"/>  
### **Result**  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/04_result1.PNG"/>
---
#
#
#
## 05. A novel deep learning based multi-class classification method for Alzheimer’s disease detection using brain MRI data (2017)
https://sci-hub.tw/10.1007/978-3-319-70772-3_20
### **Dataset**
> - MRI
### **Training**
> - 4 class classification (nondemented/very mild AD/mild AD/moderate AD)
> - Custom ConvNet similar to Inception-V4  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/05_model1.PNG" width="500"/>  
### **Result**  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/05_result1.PNG" width="500"/>
---
#
#
#
## 06. Automatic recognition of mild cognitive impairment from mri images using expedited convolutional neural networks (2017)
https://sci-hub.tw/10.1007/978-3-319-68600-4_43
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (MCI/CN)
> - Data Augmentation (brightness, horizontal and vertical shift, flipping, ...)
> - Employ different medical dataset or natural image to pre-train
> - Decompose using Tucker decomposition before the conv operation
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/06_model1.PNG" width="700"/>  
### **Result**  
> - Comparison of different tuning options  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/06_result1.PNG" width="500"/>

> - Comparison of different previous method
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/06_result2.PNG" width="450"/>
---
#
#
#
## 07. Brain MRI analysis for Alzheimer’s disease diagnosis using an ensemble system of deep convolutional neural networks (2018)
https://sci-hub.tw/10.1186/s40708-018-0080-3
### **Dataset**
> - MRI
### **Training**
> - 4 class classification (nondemented/very mild AD/mild AD/moderate AD)
> - Ensemble individual model using majority voting
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/07_model1.PNG" width="500"/>  
### **Result**  
> - Comparison of different model  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/07_result2.PNG"/>
---
#
#
#
## 08. Fusion of deep learning models of MRI scans, Mini–Mental State Examination, and logical memory test enhances diagnosis of mild cognitive impairment (2018)
https://sci-hub.tw/10.1016/j.dadm.2018.08.013
### **Dataset**
> - MRI, Mini–Mental State Examination(MMSE) result,  Wechsler Memory Scale Logical memory(LM) test result
### **Training**
> - 2 class classification (sMCI/pMCI)
> - Ensemble three VGG-11 models using majority voting
> - Ensemble three model (ensembled VGG-11, MMSE model, LM model)
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/08_model1.PNG" width="700"/>  
### **Result**  
> - Comparison of different model  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/08_result1.PNG"/>
---
#
#
#
## 09. The impact of multi-optimizers and data augmentation on TensorFlow convolutional neural network performance (2018)
https://sci-hub.tw/10.1109/mipr.2018.00032
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN)
> - Data Augmentation (rotate, crop)
> - Custom ConvNet
> - Experiment with 4 optimizer (Adagrad, Proximal-Adagrad, Adam, RMSProp
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/09_model1.PNG" width="700"/>  
### **Result**  
> - Comparison of different optimizer  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/09_result1.PNG"/>
---
#
#
#
## 10. Classification of Alzheimer’s disease based on eight-layer convolutional neural network with leaky rectified linear unit and max pooling (2018)
https://sci-hub.tw/10.1007/s10916-018-0932-7
### **Dataset**
> - MRI
### **Training**
> - 2 class classification (AD/CN)
> - Data Augmentation (rotate, noise injection, random translation, scaling, affine transform, ...)
> - Custom simple ConvNet (Conv-activation-Pool-Conv-activation .... 8 layer)
### **Result**  
> - Comparison of different classifier, number of layers  
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/10_result1.PNG" width="300"/>  

> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/10_result2.PNG" width="300"/>
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/10_result3.PNG" width="300"/>
---
#
#
#
## 11. Discrimination and conversion prediction of mild cognitive impairment using convolutional neural networks (2018)
https://sci-hub.tw/10.21037/qims.2018.10.17
### **Dataset**
> - MRI
### **Training**
> - 3 class classification (sMCI/pMCI/CN)
> - Data Augmentation (combine 3 class slice into RGB color)
> - Fine-tuning pre-trained CaffeNet, GoogleNet
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/11_model1.PNG" width="700"/>  
### **Result**  
> - Accuracy
> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/2D_slice_level_CNN/11_result1.PNG" width="400"/>
---
