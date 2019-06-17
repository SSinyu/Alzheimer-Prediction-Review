# Alzheimer Prediction Review

## Reference
Wen, J., Thibeau-Sutre, E., Samper-Gonzalez, J., Routier, A., Bottani, S., Durrleman, S., ... & Colliot, O. (2019).  
**Convolutional Neural Networks for Classification of Alzheimer's Disease: Overview and Reproducible Evaluation**.
arXiv preprint arXiv:1904.07773. [`paper`](https://arxiv.org/abs/1904.07773)
<br/>
<br/>

## Classification of Alzheimer's Disease
1. [2D slice-level CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md)
2. [3D patch-level CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_patch_level_CNN.md)
3. [ROI-based CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/ROI_based_CNN.md)
4. [3D subject-level CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md)
5. Other approach  
6. [Use clinical data](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/use_clinical_data.md)
<br/>  

## Result Table

#### Data Leakage (Non Detected) Table  

|paper|AD vs CN|sMCI vs pMCI|MCI vs CN|AD vs MCI|Multi-class|Approach|Data Leakage|
|:----|:----:|:---:|:----:|:----:|:---:|:----|:----|
|[Aderghal et al., 2017b](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/ROI_based_CNN.md#02-classification-of-smri-for-ad-diagnosis-with-convolutional-neuronal-networks-a-pilot-2d-%CF%B5-study-on-adni-2017)|0.84|-|0.65|0.67|-|ROI-based|Non detected|
|[Aderghal et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/ROI_based_CNN.md#03-classification-of-alzheimer-disease-on-imaging-modalities-with-deep-cnns-using-cross-modal-transfer-learning-2018)|0.90|-|0.73|0.83|-|ROI-based|Non detected|
|[Bäckström et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md#05-an-efficient-3d-deep-convolutional-network-for-alzheimers-disease-diagnosis-using-mr-images-2018)|0.90|-|-|-|-|3D subject-level|Non detected|
|[Cheng et al., 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_patch_level_CNN.md#classification-of-mr-brain-images-by-combination-of-multi-cnns-for-ad-diagnosis-2017)|0.87|-|-|-|-|3D patch-level|Non detected|
|[Cheng and Liu, 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md#cnns-based-multi-modality-classification-for-ad-diagnosis-2017)|0.85|-|-|-|-|3D subject-level|Non detected|
|[Islam and Zhang, 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#07-brain-mri-analysis-for-alzheimers-disease-diagnosis-using-an-ensemble-system-of-deep-convolutional-neural-networks-2018)|-|-|-|-|CN vs mild vs moderate vs severe<br/>0.93|2D slice-level|Non detected|
|[Korolev et al., 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md#residual-and-plain-convolutional-neural-networks-for-3d-brain-mri-classification-2017)|0.80|-|-|-|-|3D subject-level|Non detected|
|[Li et al., 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md#alzheimers-disease-classification-based-on-combination-of-multi-model-convolutional-network-2017)|0.88|-|-|-|-|3D subject-level|Non detected|
|[Li et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_patch_level_CNN.md#alzheimers-disease-diagnosis-based-on-multiple-cluster-dense-convolutional-networks-2018)|0.90|-|0.74|-|-|3D patch-level|Non detected|
|[Lian et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_patch_level_CNN.md#hierarchical-fully-convolutional-network-for-joint-atrophy-localization-and-alzheimers-disease-diagnosis-using-structural-mri-2018)|0.90|0.80|-|-|-|3D patch-level|Non detected|
|Mingxia Liu et al., 2018a|0.91|0.78|-|-|-|3D patch-level|Non detected|
|[Mingxia Liu et al., 2018c](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_patch_level_CNN.md#anatomical-landmark-based-deep-feature-representation-for-mr-images-in-brain-disease-diagnosis-2018)|0.91|-|-|-|-|3D patch-level|Non detected|
|[Qiu et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#08-fusion-of-deep-learning-models-of-mri-scans-minimental-state-examination-and-logical-memory-test-enhances-diagnosis-of-mild-cognitive-impairment-2018)|-|0.83|-|-|-|2D slice-level|Non detected|
|[Senanayake et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md#deep-fusion-pipeline-for-mild-cognitive-impairment-diagnosis-2018)|0.76|-|0.75|0.76|-|3D subject-level|Non detected|
|[Shmulev et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md#predicting-conversion-of-mild-cognitive-impairments-to-alzheimers-disease-and-exploring-impact-of-neuroimaging-2018)|-|0.62|-|-|-|3D subject-level|Non detected|
|[Valliani and Soni, 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#04-deep-residual-nets-for-improved-alzheimers-diagnosis-2017)|0.81|-|-|-|AD vs MCI vs CN<br/>0.57|2D slice-level|Non detected|

#### Data Leakage Table

|paper|AD vs CN|sMCI vs pMCI|MCI vs CN|AD vs MCI|Multi-class|Approach|Data Leakage|
|:----|:----:|:---:|:----:|:----:|:---:|:----|:----|
|[Aderghal et al., 2017a](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/ROI_based_CNN.md#01-fuseme-classification-of-smri-images-by-fusion-of-deep-cnns-in-2d-%CF%B5-projections-2017)|0.91|-|0.66|0.70|-|ROI-based|Unclear|
|Basaia et al., 2019|0.99|0.75|-|-|-|3D subject-level|Unclear|
|[Hon and Khan, 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#03-towards-alzheimers-disease-classification-through-transfer-learning-2017)|0.96|-|-|-|-|2D slice-level|Unclear|
|Hosseini Asl et al., 2018|0.99|-|0.94|1.00|AD vs MCI vs CN<br/>0.95|3D subject-level|Unclear|
|[Islam and Zhang, 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#05-a-novel-deep-learning-based-multi-class-classification-method-for-alzheimers-disease-detection-using-brain-mri-data-2017)|-|-|-|-|CN vs mild vs moderate vs severe<br/>0.74|2D slice-level|Unclear|
|Lin et al., 2018|0.89|0.73|-|-|-|ROI-based|Unclear|
|[Manhua Liu et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_patch_level_CNN.md#multi-modality-cascaded-convolutional-neural-networks-for-alzheimers-disease-diagnosis-2018)|0.85|0.74|-|-|-|3D patch-level|Unclear|
|[Taqi et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#09-the-impact-of-multi-optimizers-and-data-augmentation-on-tensorflow-convolutional-neural-network-performance-2018)|1.00|-|-|-|-|2D slice-level|Unclear|
|Vu et al., 2017|0.85|-|-|-|-|3D subject-level|Unclear|
|[S.-H. Wang et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#10-classification-of-alzheimers-disease-based-on-eight-layer-convolutional-neural-network-with-leaky-rectified-linear-unit-and-max-pooling-2018)|0.98|-|-|-|-|2D slice-level|Unclear|
|Bäckström et al., 2018|0.99|-|-|-|-|3D subject-level|clear|
|[Farooq et al., 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#01-a-deep-cnn-based-multi-class-classification-of-alzheimers-disease-using-mri-2017)|-|-|-|-|AD vs LMCI vs EMCI vs CN<br/>0.99|2D slice-level|clear|
|Gunawardena et al., 2017|-|-|-|-|AD vs MCI vs CN<br/>0.96|3D subject-level|clear|
|Vu et al., 2018|0.86|-|0.86|0.77|AD vs MCI vs CN<br/>0.80|3D subject-level|clear|
|[Wang et al., 2017](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#06-automatic-recognition-of-mild-cognitive-impairment-from-mri-images-using-expedited-convolutional-neural-networks-2017)|-|-|0.91|-|-|2D slice-level|clear|
|Wang et al., 2019|0.99|-|0.98|0.94|AD vs MCI vs CN<br/>0.97|3D subject-level|clear|
|[Wu et al., 2018](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md#11-discrimination-and-conversion-prediction-of-mild-cognitive-impairment-using-convolutional-neural-networks-2018)|-|-|-|-|sMCI vs pMCI vs CN<br/>0.95|2D slice-level|clear|
