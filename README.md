# ECG-Heartbeat-Classification-Using-Multimodal-Fusion

## Introduction

### In this paper, we propose two computationally efficient multimodal fusion frameworks for ECG heart beat classification called Multimodal Image Fusion (MIF) and Multimodal Feature Fusion (MFF). At the input of these frameworks, we convert the raw ECG data into three different images using Gramian Angular Field (GAF), Recurrence Plot (RP) and Markov Transition Field (MTF).  performing experiments on PhysioNet’s MIT-BIH dataset for five distinct conditions of arrhythmias which are consistent with the AAMI EC57 protocols and on PTB diagnostics dataset for Myocardial Infarction (MI) classification. 

## Experiments and Code

### 1) Download mitbih_train.csv, mitbih_test.csv, ptbdb_abnormal.csv and ptbdb_normal.csv from https://www.kaggle.com/shayanfazeli/heartbeat.
### 2) heartbeat_data_generator-MITBIH.ipynb and heartbeat_data_generator-PTB.ipynb are used to generate Grammian Angular Field (GAF) Images, Recurrence Plot (RP) Images and  Markov Transition Field (MTF) Images from MITBIH and PTB datasets respectively.
### 3) heartbeat_mit_bih_classification.ipynb and heartbeat_ptb_classification.ipynb are used for classification.
### 4) heartbeat_fusion_MITBIH.ipynb and heartbeat_fusion_ptb.ipynb are used for fusion.

## Citation

### If you find the work presented and codes useful for your research then please cite the following Paper.


