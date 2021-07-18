Problem
Classify images of skin tumors into 2 classes, benign and malignant. To predict if it is cancer or not.

Data used
Images 224 x 224
Train dataset
Malignant: 1197 images
Benign: 1440 images
Test dataset  (20% dataset)
Malignant: 300 images
Benign: 360 images

Model used

Type	Kernel	Stride	Padding	Input/ output size	Activation
Convolution2D	3x3	1	1	3 x 64	ReLU
MaxPool2D	2x2/ 2	2			
Convolution2D	3x3	1	1	64x128 	ReLU
MaxPool2D	2x2/ 2	2			
Convolution2D	3x3	1	1	128x512	ReLU
MaxPool2D	2x2/ 2	2			
Convolution2D	3x3	1	1	512x512	ReLU
MaxPool2D	2x2/ 2	2			
Convolution2D	3x3	1	1	512x512	ReLU
MaxPool2D	2x2/ 2	2			
Dropout (0.5)					
Linear				512*7*7 x 4096	ReLU
Linear				4096 x 2	Tanh


Training
Optim : Adam
Cost function : CrossEntropyLoss
Learning rate = 0.000001
Batch = 10
Epochs = 200

Results
Accuracy: 86%
Accuracy malignant: 84%
Accuracy benign: 94%