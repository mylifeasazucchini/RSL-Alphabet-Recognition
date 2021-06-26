# RSL-Alphabet-Recognition

This repository is primarily aimed to use Deep Learning to recognize the alphabets from the Russian Sign Language (RSL). 

# The core objectives of this mini-project are:
1. Achieving accuracy similar to what Deep Learning has brought to recognition of other sign languages such as the American Sign Language.
2. Handling data scarcity 

# Dataset

Courtesy of: https://github.com/hse-sl/rsl-alphabet-dataset (20 images/ alphabet)

# Results with Transfer Learning
### resnet34 - epochs = 15 - max_lr = 0.01 - val_acc: 0.6719
### resnet34 - epochs = 15 - max_lr = 0.001 - val_acc: 0.8281
### resnet50 - epochs = 15 - max_lr = 0.0025 - val_acc: 0.7203¶
### resnet50 - epochs = 30 - max_lr = 0.001 - val_acc: 0.8594

# Next Step: 
### 1. Employ Few Shot Learning
