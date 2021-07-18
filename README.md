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

### References
- https://www.cdc.gov/spanish/cancer/skin/basic_info/index.htm
- https://es.wikipedia.org/wiki/C%C3%A1ncer_de_piel
- https://www.mayoclinic.org/es-es/diseases-conditions/skin-cancer/symptoms-causes/syc-20377605
- https://thesai.org/Downloads/Volume10No7/Paper_46-Convolutional_Neural_Network.pdf
- https://www.kaggle.com/fanconic/skin-cancer-malignant-vs-benign/kernels
- https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
- https://adventuresinmachinelearning.com/convolutional-neural-networks-tutorial-in-pytorch/
- https://towardsdatascience.com/batch-normalization-and-dropout-in-neural-networks-explained-with-pytorch-47d7a8459bcd
- https://www.bbc.com/mundo/noticias/2015/05/150504_salud_cancer_piel_il
