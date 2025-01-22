# Welcome to TensorFlow repository!
This personal code repository contains a range of artificial intelligence and numerical data processing projects. The models are coded in Python and use the framework Tensorflow/Keras. Python scripts are in Jupyter notebook format, and can be run locally or on Google Colab. All elements of the repository are licensed under the *GNU General Public License v3.0* (see License section). 

---------------
## Why did I create this project?
The idea for this project was born at the end of my engineering degree, during my end-of-study internship. I was working on machine learning and Gaussian processes in order to make regressions and then predictions for a finite element analysis problem. Passionate about the field, I decided to learn more about the essential tools of machine/deep learning. I followed a free online training course offered in partially by Keras (https://www.tensorflow.org/tutorials). I started by completing part of the training step-by-step, then merged multiple codes into one to obtain more complex and optimized neural networks. 

---------------
## What's in this code repository?

In this repository, Python scripts can be used to build and train neural networks (NN) for a wide range of applications. You'll find:
1. **Image recognition**: basic image classification (with hyperparameter tuning) 
2. **Movie review classification**: binary text classification (tokenisation method + embedding space exploration)
3. **Fuel efficiency predictions**: regression task and prediction (model comparison)
4. **Flower classification**: convolutional network 
5. **Flower classification by transfert learning**: classify images with a pre-trained model (with MobileNet V2 network)
6. **Brain cancer detection**: semantic image segmentation classification (with U-Net network)
7. **Word embeddings** with the skip-Gram algorithm (!!In progress!!)

---------------
## How to use it? 
If you want to run a Python script in Google Colab, it's extremely simple: you need just a Google account. 

1. **Select the script to be executed and open it in Google Colab** (you may be asked to connect to your Google). The code opened on Google colab is a copy of the original Jupyter notebook. Feel free to modify parts of the code and/or comments.

![Capture d’écran 2024-11-12 à 11 17 06](https://github.com/user-attachments/assets/f587d0d0-b8d5-48f6-8f2f-3a8bff9c1252)

2. **Go to the Input section to complete them**. Most neural networks have already been trained and optimized: parameters associated with each neuron have already been calculated. You can choose whether to use these parameters (complete No in this case) or train again the network (Yes).

![Capture d’écran 2024-11-12 à 11 17 50](https://github.com/user-attachments/assets/9c351c50-f1a7-47d9-bd6e-e8b10db5e41b)

3. **Connect to a calculation unit by clicking on *reconnect*** (a). Once connected, click on *RAM Disk* to view your machine's characteristics (b). Google Colab offers a limited but sufficient runtime. To change the execution type, click on *Modify execution type* (c). Select CPU or T4 GPU when recommended (d).

![Capture d’écran 2024-11-12 à 11 18 16](https://github.com/user-attachments/assets/dc202eaf-0691-4113-88ab-b8be96900b7f)

4. Finally, go to ***Run* and click on *Run all***. Once finished, browse the notebook to view the results.
   
![Capture d’écran 2024-11-12 à 11 18 35](https://github.com/user-attachments/assets/6019a3ff-937c-47be-b358-dad6b16f7772)

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
This repository was created and managed by Benjamin. To contact me, send me an email on benjaminmorel27@gmail.com 
