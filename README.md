** This is a QMUL MSc assignment that contains a computer vision (CV) model for identifying plants body parts **

The notebook holds four types of neural networks (NN):
1) Basic Neural Network (23 minutes to train)
2) Small Neural Network (13 minutes to train)
4) Big Neural Network (45 minutes to train)
5) Convoluted Neural Network (2 hours to train)

The model was trained on CPU

Version of python and supporting libraries:
- Python: 3.10.11
- Tensorflow: 2.18.0
- Numpy: 2.0.2
- Pandas: 2.2.3
- Matplotlib: 3.10.1
- SKLearn: 1.6.1
- SciPy: 1.15.2
- rdata: 0.11.2

All of the models are trained using the KewMNIST dataset (not publicly available)

## Basic EDA - Label Distribution
![Label Dist for KewMNIST dataset](https://github.com/HA-141/QMUL-MSC-assignment-CV-for-identifying-plant-body-parts/blob/main/images/KewMNIST_Label_Dist.png)

Each models is trained on a train-test split of 120 training samples stratified by their label and used least confidence active learning until training data reached 90% of total dataset

## Model accuracy and loss over iterations

### Basic NN

<img src="https://raw.githubusercontent.com/HA-141/QMUL-MSC-assignment-CV-for-identifying-plant-body-parts/main/images/Basic_NN_performance.png" width="500" height="300">

### Small NN 

![SNN Performance](https://github.com/HA-141/QMUL-MSC-assignment-CV-for-identifying-plant-body-parts/blob/main/images/Small_NN_performance.png)

### Big NN 

![BNN Performance](https://github.com/HA-141/QMUL-MSC-assignment-CV-for-identifying-plant-body-parts/blob/main/images/Big_NN_performance.png)

### CNN

![CNN Performance](https://github.com/HA-141/QMUL-MSC-assignment-CV-for-identifying-plant-body-parts/blob/main/images/CNN_performance.png)

### MCC Scores over iterations for every model 

![MCC scores](https://github.com/HA-141/QMUL-MSC-assignment-CV-for-identifying-plant-body-parts/blob/main/images/MCC_for_all_models.png)

### F1 scores over iterations for every model

![F1 Scores](https://github.com/HA-141/QMUL-MSC-assignment-CV-for-identifying-plant-body-parts/blob/main/images/F1_for_all_models.png)
