# DF-Capstone-Handwritten-Greek-Letter-Classification


## Handwritten Greek Letter Classification Project

This is my final project for Digital Futures Academy, attempting to classify images of handwritten Greek letters using Convolutional Neural Networks.


<img align="right" height="320px" src="https://user-images.githubusercontent.com/99501368/154052415-7f133c15-3f74-49c7-9c19-b05bd854888e.jpeg">

### Description:
Driven by my love/hate relationship with having to write some of the Greek letters during my Mathematics degree I accepted the task of trying to classify some images of handwritten Greek letters that are most commonly used in Mathematics. The images of these letters are a subset of a larger dataset known as HASYv2 courtesy of 'Thoma, Martin. "The hasyv2 dataset." arXiv preprint arXiv:1701.08380 (2017)' and is composed of nearly 170,000 32x32 black and white images of 369 different mathematical symbols and characters. The subset that I worked with in this project, 38 different letters, is composed of a variety of lower case, upper case and variant (different ways to write the same Greek letter) letters which can be seen in the image to the right. There are 31,520 such images. In this project I use a variety of convolutional neural networks to these classify these images.


### Conclusions:
To evaluate the performance of the final model that I selected, a convolutional neural network, I used 5-fold cross validation and obtained a mean accuracy result of 0.878. Additionally I also created my own images by handwritting the 38 different Greek letters used in this project and evaluated the final models performance on these images. The model correctly classified 29/38 (76.3%) images correctly.

---

This repository consists of the project notebook and presenation. 

As mentioned above, the dataset used in this project can be located using the paper: 'Thoma, Martin. "The hasyv2 dataset." arXiv preprint arXiv:1701.08380 (2017)'. The file is a tar.bz file and I have left code at the top of the workbook that will extract the files for you. 
