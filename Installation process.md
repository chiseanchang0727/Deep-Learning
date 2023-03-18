# Install CUDA toolkit

1. open NVIDIA website: [Link](https://developer.nvidia.com/cuda-downloads)
2. select based on your PC condition and download the version you want
  <img src="https://user-images.githubusercontent.com/113814545/226090862-aef2c3f0-2ab0-446e-a26f-e04709a8f01c.png" width="550">
3. start installation by double clicking what you just download


# Install cuDNN
1. Create an Nvidia account or sign in using Google or Facebook. Once logged in you can download the cuDNN
2. the download link : https://developer.nvidia.com/cudnn (it's a ZIP file)
3. unzip and copy the folder to C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA

![image](https://user-images.githubusercontent.com/113814545/226091413-13c8f4fc-70a9-4f54-9bb9-35e4d5e103c6.png)

## TO THIS FOLDER 

![image](https://user-images.githubusercontent.com/113814545/226091448-49aa8735-78b4-4d8d-95d6-0f003f7f32b2.png)


# Set Environment variable

1. Open the environment variable panel
  <img src="https://user-images.githubusercontent.com/113814545/226091188-c4e85804-893c-4fe8-a86d-e4da6fa55410.png" width="700">
  
2. The 'CUDA_PAHT' and 'CUDA_PATH_V12.1' is usually well-set after installing CUDA. If not, add it.
  <img src="https://user-images.githubusercontent.com/113814545/226091557-74f3c48b-5323-438d-ab6d-2f4b185e5d3a.png" width="600">

3. Create 'CUDNN' and add the following directories
  
  <img src="https://user-images.githubusercontent.com/113814545/226091659-3f5744bf-9ba9-42a2-8a13-789b929ee849.png" width="600">
  
      C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.1;
      C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.1\bin;
      C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.1\include;
      C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.1\lib;
  

4. Add the directories to 'path' 

  <img src="https://user-images.githubusercontent.com/113814545/226092197-39a227f7-5d74-406c-9c6a-1998c18fc527.png" width="600">

# Install Tensorflow/Keras

- If the Python is installed by Anaconda, then open the Anaconda promopt
- enter the following commnad for installing Tensorflow
```python!
pip install tensorflow
```
- Then install Keras
```
pip install keras
```

Check if the installation is done by import Tensorflow/Keras in .ipynb
  <img src="https://user-images.githubusercontent.com/113814545/226092816-fc4e05f5-444d-449e-9514-37ff45042e8e.png" width="600">
  

