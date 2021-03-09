# how-to-use-gpu-in-tensorflow
---
## 1. Check graphics card 
1) windowkey + x -> Device Manager
2) Check the graphic card in the device manager

## 2. Check whether GPU computation is compatible
1. Search "cuda gpu" on Google(or https://developer.nvidia.com/cuda-gpus)
2. click CUDA-Enabled GeForce Product
3. There is a list of graphics cards that can use the CUDA toolkit (to use gpu compute capability must be greater than 3.0)

## 3. CUDA toolkit archive
1. Search "cuda toolkit archive" 
2. Choose the option that suits your computer environment and install it.

## 4. Install cuDNN Library 
1. Search "cudnn" (or https://developer.nvidia.com/cudnn)
2. To install cudnn library, you have to sign up NVIDIA Developer

## 5. copy & paste to cuda folder
1. Copy the "bin", "include", "lib" folder of the cuDNN library installed in step 4.
2. Paste to C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.0

## 6. Make sure to use GPU
- import tensorflow and excute your code  
-    
  ![그림1](https://user-images.githubusercontent.com/55774589/110428166-34b75780-80ec-11eb-83eb-d5d2d1b61687.png)
