## Problem
Classify images of skin tumors into 2 classes, benign and malignant. To predict if it is cancer or not.

## Data used
- Images 224 x 224
- Train dataset
  - Malignant: 1197 images
  - Benign: 1440 images
- Test dataset  (20% dataset)
  - Malignant: 300 images
  - Benign: 360 images

## Model used

![image](https://user-images.githubusercontent.com/46162626/126080705-15107dc2-bcda-45bc-aa15-dbcb95a0a84a.png)

## Training
- Optim: Adam
- Cost function: CrossEntropyLoss
- Learning rate: 0.000001
- Batch: 10
- Epochs: 200

## Results
- Accuracy: 86%
- Accuracy malignant: 84%
- Accuracy benign: 94%
