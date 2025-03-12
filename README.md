# Welcome to TensorFlow repository!
This personal code repository contains a range of artificial intelligence and numerical data processing projects. The models are coded in Python and use the framework Tensorflow/Keras. Python scripts are in Jupyter notebook format, and can be run locally or on Google Colab. All elements of the repository are licensed under the *GNU General Public License v3.0* (see License section). 

---------------
## Why did I create this project?
The idea for this project was born at the end of my engineering degree, during my end-of-study internship. I was working on machine learning and Gaussian processes in order to make regressions and then predictions for a finite element analysis problem. Passionate about the field, I decided to learn more about the essential tools of machine/deep learning. I followed a free online training course offered in partially by Keras (https://www.tensorflow.org/tutorials). I started by completing part of the training step-by-step, then merged multiple codes into one to obtain more complex and optimized neural networks. 

---------------
## What's in this code repository?

In this repository, Python scripts are used to build and train neural networks (NN) for a wide range of applications: NLP, CV, RP (Prediction Regression), UL (Unsupervised Learning), OTP (Optimization), PINN (Physics-Informed Neural Networks) and HW ("Hello World"). Therefore, you will find:
1. **[HW] Image recognition**: basic image classification (with hyperparameter tuning) 
2. **[NLP] Movie review classification**: binary text classification (with a sensitivity analysis)
3. **[RP] Fuel efficiency predictions**: regression and prediction (model confrontation)
4. **[CV] Flower classification**: convolutional network 
5. **[CV] Flower classification by transfert learning**: complex convolutional pre-trained model (MobileNet V2)
6. **[CV] Brain cancer detection**: semantic image segmentation classification (with U-Net)
7. **[NLP] Word2vec**: word embedding built with skip-Gram method
8. **[NLP] Recurrent neural network**: text classification (with LSTM layers)
9. **[UL] Word embedding space**: visualization and NLP model comparison (with PCA/t-SNE reduction)
10. **[OTP] Model pruning**: sparse model and compression (with low magnitude weights suppression)
11. **[PINN] PDE resolution model**: application for heat diffusion in stars (!! IN PROGRESS !!)

---------------
## How to use it? 
If you want to run a Python script in Google Colab, it's extremely simple: you need just a Google account. 

1. **Select the script to be executed and open it in Google Colab** (you may be asked to connect to your Google). The code opened on Google colab is a copy of the original Jupyter notebook. Feel free to modify parts of the code and/or comments.

![github1](https://github.com/user-attachments/assets/70b125a9-7340-4133-844d-04098391921c)

2. **Connect to a calculation unit by clicking on *connect*** (a). Once connected, click on *RAM Disk* to view your machine's characteristics (b). Google Colab offers a limited but sufficient runtime. To change the execution type, click on *change runtime type* (c). Select CPU or T4 GPU when recommended (d). Note that when the script runs on CPU, a pre-trained model is used to save time, computer resources and CO2. 

![github2](https://github.com/user-attachments/assets/1048bce1-1699-4316-ab55-0de25cf0a4d9)

3. Finally, go to ***Runtime* and click on *Run all***. Once finished, browse the notebook to view the results.

![github3](https://github.com/user-attachments/assets/6eb0ab78-5d11-4bf6-bac4-536d714ff65f)

---------------
## Tech & requirements
Here are the libraries and packages commonly used in my Python codes. All are free and easy to install!

*   [numpy](https://numpy.org/doc/stable/index.html) - 1.26 version - fundamental package for scientific computing with Python
*   [pandas](https://pandas.pydata.org/docs/index.html) - 2.2.3 version - open source library for data manipulation and analysis
*   [pillow](https://pillow.readthedocs.io/en/stable/#) - 10.4.0 version - Python imaging library
*   [matplotlib](https://matplotlib.org/stable/) - 3.10 version - Python 2D plotting library
*   [plotly](https://plotly.com/graphing-libraries/) - 5.24 version - interactive charts and maps for Python
*   [pytorch](https://pytorch.org/) -2.2.2 version - open source deep learning platform
*   [tensorflow](https://www.tensorflow.org/) - 3.10.12 version - open source library for numerical computation and large-scale machine learning

Python 3.10

---------------
This repository was created and managed by Benjamin. To contact me, send me an email on contact.upside830@silomails.com
