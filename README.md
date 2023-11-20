# Siamese Convolutional Neural Network for the Classification  of Peach Leaves. 

This work focuses on the use of Siamese CNNs to identify the front and back faces of six Peach leaf varieties, which play a crucial role prior to detecting bacteriosis, a common disease in Peach production.

## Dataset
The dataset is available at https://drive.google.com/drive/folders/1rWCr9DrknoK0HKFhNRavCVgZ5UKjU3hi. The experiments developed were
applied to the 224x224 variant of the dataset. 

## Architectures
The models developed for this work were
separated into different colab notebooks, each having the following names:

### Replication of benchmark architecture
siamese_network_benchmark.ipynb

### Proposed architecture ReLU variant
siamese_network_pa_relu.ipynb

### Proposed architecture LReLU variant
siamese_network_pa_lrelu.ipynb

### Proposed architecture ELU variant
siamese_network_pa_elu.ipynb

### Pre-trained model ResNet50 
siamese_network_pm_resnet50.ipynb

### Pre-trained model DenseNet121 
siamese_network_pm_densenet121.ipynb

### Pre-trained model EfficientNetB0 
siamese_network_pm_efficientnetb0.ipynb

## Replication of Results

1. Download the 224x224 variant of the dataset
2. Clone this repository
3. Upload the dataset to your Google Drive account
5. Open Google Colab and upload one of the 
   architecture files you want to test
6. Follow the steps mentioned in the colab notebook
   to train the models and check for the results
