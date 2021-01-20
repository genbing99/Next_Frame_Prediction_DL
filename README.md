# What's Next? Next Frame Prediction with Deep Learning Approach

A project for predicting future frames based on historical frames. Deep learning approaches are experimented in this project. We proposed Convolutional 3D Network with Encoding Forecasting Structure to deal with the next 20 frames prediction. 

If you have any inquiries, please email me at genbing67@gmail.com or the collaborators, Ngiu Jin Tian Ci (j1nngiu@gmail.com) and Leow Yen Siang (yensiang99@hotmail.com).

## Result

### Moving MNISt 
Quantitative Result:</br>
<img src='images/MNIST_Result.PNG' width=250 height=300>

Qualitative Result:</br>
<img src='images/MNIST_Visual.PNG' width=700 height=300>

### Moving Shapes
Quantitative Result:</br>
<img src='images/Shapes_Result.PNG' width=250 height=300>

Qualitative Result:</br>
<img src='images/Shapes_Visual.PNG' width=700 height=300>

### To Reproduce Result
Please download the dataset at https://drive.google.com/drive/folders/10mqCXyCGlWw7HEa1RT-ZYx9j5mYC7yfh?usp=sharing, and placed in the required structure according to the dataset location for example:
>├─Moving_Shapes <br>
>>├─Conv3D.ipynb <br>
>>├─moving-shapes-3-te-images.npy <br>

>├─Moving_MNIST <br>
>>├─Conv3D.ipynb <br>
>>├─moving-mnist-3-te-images.npy <br>

Paper: https://drive.google.com/file/d/1JHIHGNiIP1zouaL_VW7iTmUfmBk_Eoz9/view?usp=sharing </br>
Presentation Slides: https://drive.google.com/file/d/1O9KPaHwLM0fZeqjluMSLa7CtY_KA9qRR/view?usp=sharing </br>

### Note
For VRNN, you have to run the VRNN_Train.ipynb to get the model weights before evaluation with VRNN_Test.ipynb.
