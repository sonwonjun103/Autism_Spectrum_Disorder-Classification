# Autism_Spectrum_Disorder-Classification
From 2023.01.31~Present

### 2023.01.30
1. Download Data
2. Make Label
3. Build 3D ResNet Model

### 2023.01.31
1. Cropping

### 2023.02.01
1. Plus Dropout
2. To reduce T1 Image size, reduce slice 100

### 2023.02.04
1. Plus L2 norm to Loss function

### 2023.02.05
1. To balance classification label, augment TC dataset with horizontal flip and vertical flip

### 2023.02.06
1. Change batch size 
T1 : 2->8
T2 : 8->16
2. Plus nn.ReduceLrOnPleatu

------------------------------------------------------------------------------------------------------------

### 2023.02.07
1. Plus augmentation skill : Rotate
2. Study Convolution 3D more ==> (Batch, channel, depth, height, width)
3. Change Image size (T1 : (100,256,256), T2:(34,256,256))

### 2023.02.11~2023.02.12
1. DTI processing
2. Visualize DTI images

### 2023.02.17~2023.02.18
1. Use data that age is more than 3

### 2023.02.21
1. Use Data that age is more than 3
2. T1+T2 

### 2023.02.22
1. T1+T2 (over age 3)

### 2023.02.23~
1. change rotate range (0,10)
2. change model
3. remove vertical augmentation
4. search another augmentation
