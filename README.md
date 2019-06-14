# Alzheimer Prediction Review

## Classification of Alzheimer's Disease
1. [2D slice-level CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/2D_slice_level_CNN.md)
2. [3D patch-level CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_patch_level_CNN.md)
3. [ROI-based CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/ROI_based_CNN.md)
4. [3D subject-level CNN](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/3D_subject_level_CNN.md)
5. [Ohter approach](https://github.com/SSinyu/Alzheimer-Prediction-Review/blob/master/other_approach.md)  
<br/>  

## Result Table

### Data Leakage (Non Detected) Table  

|paper|AD vs CN|sMCI vs pMCI|MCI vs CN|AD vs MCI|Multi-class|Approach|Data Leakage|
|:----|:----:|:---:|:----:|:----:|:---:|:----|:----|
|Aderghal et al., 2017b|0.84|-|0.65|0.67|-|ROI-based|Non detected|
|Aderghal et al., 2018|0.90|-|0.73|0.83|-|ROI-based|Non detected|
|Bäckström et al., 2018|0.90|-|-|-|-|3D subject-level|Non detected|
|Cheng et al., 2017|0.87|-|-|-|-|3D patch-level|Non detected|
|Cheng and Liu, 2017|0.85|-|-|-|-|3D subject-level|Non detected|
|Islam and Zhang, 2018|-|-|-|-|CN vs mild vs moderate vs severe<br/>0.93|2D slice-level|Non detected|
|Korolev et al., 2017|0.80|-|-|-|-|3D subject-level|Non detected|
|Li et al., 2017|0.88|-|-|-|-|3D subject-level|Non detected|
|Li et al., 2018|0.90|-|0.74|-|-|3D patch-level|Non detected|
|Lian et al., 2018|0.90|0.80|-|-|-|3D patch-level|Non detected|
|Mingxia Liu et al., 2018a|0.91|0.78|-|-|-|3D patch-level|Non detected|
|Mingxia Liu et al., 2018c|0.91|-|-|-|-|3D patch-level|Non detected|
|Qiu et al., 2018|-|0.83|-|-|-|2D slice-level|Non detected|
|Senanayake et al., 2018|0.76|-|0.75|0.76|-|3D subject-level|Non detected|
|Shmulev et al., 2018|-|0.62|-|-|-|3D subject-level|Non detected|
|Valliani and Soni, 2017|0.81|-|-|-|AD vs MCI vs CN<br/>0.57|2D slice-level|Non detected|

### Data Leakage Table

|paper|AD vs CN|sMCI vs pMCI|MCI vs CN|AD vs MCI|Multi-class|Approach|Data Leakage|
|:----|:----:|:---:|:----:|:----:|:---:|:----|:----|
|Aderghal et al., 2017a|0.91|-|0.66|0.70|-|ROI-based|Unclear|
|Basaia et al., 2019|0.99|0.75|-|-|-|3D subject-level|Unclear|
|Hon and Khan, 2017|0.96|-|-|-|-|2D slice-level|Unclear|
|Hosseini Asl et al., 2018|0.99|-|0.94|1.00|AD vs MCI vs CN<br/>0.95|3D subject-level|Unclear|
|Islam and Zhang, 2017|-|-|-|-|CN vs mild vs moderate vs severe<br/>0.74|2D slice-level|Unclear|
|Lin et al., 2018|0.89|0.73|-|-|-|ROI-based|Unclear|
|Manhua Liu et al., 2018|0.85|0.74|-|-|-|3D patch-level|Unclear|
|Taqi et al., 2018|1.00|-|-|-|-|2D slice-level|Unclear|
|Vu et al., 2017|0.85|-|-|-|-|3D subject-level|Unclear|
|S.-H. Wang et al., 2018|0.98|-|-|-|2D slice-level|Unclear|
|Bäckström et al., 2018|0.99|-|-|-|-|3D subject-level|clear|
|Farooq et al., 2017|-|-|-|-|AD vs LMCI vs EMCI vs CN<br/>0.99|2D slice-level|clear|
|Gunawardena et al., 2017|-|-|-|-|AD vs MCI vs CN<br/>0.96|3D subject-level|clear|
|Vu et al., 2018|0.86|-|0.86|0.77|AD vs MCI vs CN<br/>0.80|3D subject-level|clear|
|Wang et al., 2017|-|-|0.91|-|-|2D slice-level|clear|
|Wang et al., 2019|0.99|-|0.98|0.94|AD vs MCI vs CN<br/>0.97|3D subject-level|clear|
|Wu et al., 2018|-|-|-|-|sMCI vs pMCI vs CN<br/>0.95|2D slice-level|clear|
