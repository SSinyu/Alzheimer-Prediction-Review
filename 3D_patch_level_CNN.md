
## 01. CNNs based multi-modality classification for AD diagnosis (2017)
https://sci-hub.tw/10.1109/cisp-bmei.2017.8302281
> ### **Dataset**
>> - MRI, PET
> ### **Training**
>> - 2 class classification (AD/CN)
>> - Extract feature with 3D ConvNet
>> - Combined feature vector of MRI and PET
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_model1.PNG" width="450"/>  
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_model2.PNG" width="600"/>
> ### **Result**  
>> - Comparison of different method
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_result1.PNG"/>  
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/01_result2.PNG"/>
---
#
#
#
## 02. Multi-modality cascaded convolutional neural networks for Alzheimer’s disease diagnosis (2018)
https://sci-hub.tw/10.1007/s12021-018-9370-4
> ### **Dataset**
>> - MRI, PET
> ### **Training**
>> - 2 class classification (AD/CN, pMCI/CN, sMCI/CN)
>> - Divide into 3x3x3 size from whole brain image --> extract 27 patches
>> - Extract feature with 3D ConvNet
>> - Combined feature vector of MRI and PE
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/02_model1.PNG" width="700"/>  
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/02_model2.PNG" width="700"/>
> ### **Result**  
>> - Comparison of different method
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/02_result1.PNG"/>
---
#
#
#
## 03. Alzheimer's disease diagnosis based on multiple cluster dense convolutional networks (2018)
https://sci-hub.tw/10.1016/j.compmedimag.2018.09.009
> ### **Dataset**
>> - MRI
> ### **Training**
>> - 2 class classification (AD/CN, MCI/CN)
>> - Find the groups of patches by K-means clustering (32x32x32 size)
>> - Reduce feature dimension by PCA (32x32x32 --> 2000 dim)
>> - Fine-tuning pre-trained 3D DenseNet
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/03_model1.PNG" width="700"/>  
> ### **Result**  
>> - Comparison of different model
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/03_result1.PNG" width="700"/>

>> - Comparison of different feature extraction
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/03_result2.PNG" width="700"/>
---
#
#
#
## 04. Hierarchical Fully Convolutional Network for Joint Atrophy Localization and Alzheimer's Disease Diagnosis using Structural MRI (2018)
https://sci-hub.tw/10.1109/tpami.2018.2889096
> ### **Dataset**
>> - MRI
> ### **Training**
>> - 2 class classification (AD/CN, pMCI/sMCI)
>> - Data Augmentation (random flipping, ditorting, shifting)
>> - Process each patch by patch-level sub-networks (shared parameter) and concat each ouput feature
>> - Repeat feature encoding by region-level and subject-level networks
>> Delete uninformative sub-networks (Network Pruning)
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/04_model1.PNG" width="800"/>  

>> - Hybrid loss function (cross entropy with patch-/region-/subject-level networks)
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/04_loss1.PNG" width="500"/>
> ### **Result**  
>> - Comparison of different model
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/04_result1.PNG"/>

>> - Visualize patch-, region-level locations
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/04_vis1.PNG" width="600"/>
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/04_vis2.PNG" width="600"/>
---
#
#
#
## 05. Anatomical landmark based deep feature representation for MR images in brain disease diagnosis (2018)
https://sci-hub.tw/10.1109/jbhi.2018.2791863
> ### **Dataset**
>> - MRI
> ### **Training**
>> - 2 class classification (AD/CN)
>> - Find landmark locations and projected to images
>> - Extract patches from each landmark locations and learn features
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/05_model1.PNG" width="700"/>  
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/05_model2.PNG" width="700"/>
> ### **Result**  
>> - Comparison of different model
>> <img src="https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/img/3D_patch_level_CNN/05_result1.PNG"/>
