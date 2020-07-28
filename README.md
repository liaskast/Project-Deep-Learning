# Deep Learning Project
This repository contains my work for the Deep Learning (EE3-23) course of Imperial College London's Electrical & Electronic School of Engineering.

## Deliverables
 - ### Report
 The main deliverable for this course was the composition of a report outlining the findings observed upon the completion of all the notebooks. The report summarizing those findings can be found [here](Report.pdf).

## Instructions

Throughout this course we used Python and [Jupyter Notebook](https://jupyter.org/), and [Keras](https://keras.io/) as the deep learning framework.
Also, the tutorials use [Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb), which is a free Jupyter notebook environment that runs in the cloud. 

Each of the notebooks contains this image


<p align="center">
<img src ="https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667" />
</p>

which when clicked takes you to the Colaboratory website. 

Colaboratory provides free GPU, so you can modify part of the tutorials and retrain the models to test your modifications. Specifically, you get 12 hours of continuous access to a k80 GPU. When those 12 hours are over, you can connect to another machine. This [Notebook](https://colab.research.google.com/notebooks/gpu.ipynb#scrollTo=3IEVK-KFxi5Z) shows a comparison of the CPU vs GPU speed up in Colaboratory. The Hardware accelerator can be selected in Edit->Notebook Settings. There is also the option of using Tensor Processor Units (TPUs), but the tutorials will only use the GPU. Here is an [example notebook](https://colab.research.google.com/notebooks/tpu.ipynb) using TPUs.   

## Links to the notebooks
Sometimes the notebooks do not render correctly in GitHub. You can access directly the notebook in the Colab environment using the following links.
### Chapter 1
  * [Python part 1](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_01_part1_Python.ipynb)
  * [Python part 2](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_01_part2_Python.ipynb)
  * [Keras](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_01_part3_Keras.ipynb)
### Chapter 2
  * [Introduction to CNNs](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_02_CNN_Introduction.ipynb)
### Chapter 3
  * [Evaluation Measures](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_03_Evaluation_Measures.ipynb)
### Chapter 4
  [04/02/20] Updated the tutorial removing the lr_normalizer line in the model_scan function when using talos, which was scaling the learning rate

  * [Network Training](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_04_Network_Training.ipynb) 
  
### Chapter 5
[28/02/20] Removed Task 2, ResNet coding and training, from tutorial.

[1/03/20] Moved back to SGD optimiser instead of Adam in Tutorial 5.

  * [Introduction to Convolutional Neural Networks Architectures](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_05_CNN_architectures.ipynb)
  
### Chapter 6
  * [Recurrent Neural Networks (RNN)](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_06_RNN.ipynb)
  
### Chapter 7
  * [Autoencoders](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_07_Autoencoders.ipynb)
 
### Chapter 8
  * [VAE-GAN](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_08_VAE_GAN.ipynb)
  
### Chapter 9
  * [Reinforcement Learning](https://colab.research.google.com/github/MatchLab-Imperial/deep-learning-course/blob/master/2020_09_RL.ipynb)
  
  

