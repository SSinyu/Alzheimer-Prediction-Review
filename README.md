# AD clf
-----------

### 01. Deep Structural and Clinical Feature Learning for Semi-Supervised Multiclass Prediction of Alzheimer’s Disease (2018)
(https://sci-hub.tw/https://ieeexplore.ieee.org/abstract/document/8623946)
#### **INPUT** 
- For each selected sample, 88 FreeSurfer processed regional
baseline longitudinal MR features such as volume, surface
area and cortical thickness, and 11 cognitive test features.
#### **TRAINING**
![01_model](https://github.com/SSinyu/p/blob/master/img/01_model.PNG)
- Sparse Autoencoder based feature learning
- pretrained weight + logistic layer
#### **RESULT**
- SVM-based methods
<img src="https://github.com/SSinyu/p/blob/master/img/01_result1.PNG" width="550"/> 
- Deep learning methods
<img src="https://github.com/SSinyu/p/blob/master/img/01_result2.PNG" width="550"/> 

--------

### 02. Deep learning reveals Alzheimer's disease onset in MCI subjects: Results from an international challenge (2018) 
(https://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S0165027017304296)
#### **INPUT**
- Subcortical volumes, cortical thickness, cortical volume, cor tical surface area, cortical thickness standard deviation, cortical curvature and hippocampal subfields’ volumes resulted by FreeSurfer.(https://inclass.kaggle.com/c/mci-prediction/data)
#### **TRAINING**
- select features by Random Forest
- DNN training
<img src="https://github.com/SSinyu/p/blob/master/img/02_model.PNG" width="400"/> 

#### **RESULT**
<img src="https://github.com/SSinyu/p/blob/master/img/02_result1.PNG" width="550"/> 
<img src="https://github.com/SSinyu/p/blob/master/img/02_result2.PNG" width="550"/>

--------

### 03. Disease Prediction using Graph Convolutional Networks: Application to Autism Spectrum Disorder and Alzheimer’s Disease (2018)
(https://arxiv.org/pdf/1806.01738.pdf)
#### **INPUT**
- use the volumes of all C = 138 segmented brain structures.
- + graph information (age, sex, genetic info)
#### **TRANINIG**
- Graph Convolutional networks
![03_model](https://github.com/SSinyu/p/blob/master/img/03_model.PNG)
#### **RESULT**
- Influence of polynomial order
![03_result1](https://github.com/SSinyu/p/blob/master/img/03_result1.PNG)
- Influence of phenotypic measures
![03_result2](https://github.com/SSinyu/p/blob/master/img/03_result2.PNG)

--------

# Tabular data application
-----------

### 01. SuperTML: Two-Dimensional Word Embedding for the Precognition on Structured Tabular Data (2019)
(https://arxiv.org/pdf/1903.06246v3.pdf)
#### **TRAINING**
- images with two-dim embeddings of the features in tabular data
![_01_data1](https://github.com/SSinyu/p/blob/master/img/_01_data1.PNG)
![_01_data2](https://github.com/SSinyu/p/blob/master/img/_01_data2.PNG)
- fine-tuning the pretrained CNN model.
#### **RESULT**
![_01_result1](https://github.com/SSinyu/p/blob/master/img/_01_result1.PNG)
![_01_result2](https://github.com/SSinyu/p/blob/master/img/_01_result2.PNG)

--------

### 02. Regularization Learning Networks: Deep Learning for Tabular Datasets (2018)
(https://arxiv.org/pdf/1805.06440v3.pdf)

--------


