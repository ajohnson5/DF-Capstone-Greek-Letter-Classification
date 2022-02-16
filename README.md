# DF-Capstone-Handwritten-Greek-Letter-Classification


## Handwritten Greek Letter Classification Project

This is my final project for Digital Futures Academy, attempting to classify images of handwritten Greek letters using Convolutional Neural Networks.


<img align="right" height="320px" src="https://user-images.githubusercontent.com/99501368/154052415-7f133c15-3f74-49c7-9c19-b05bd854888e.jpeg">

### Description:
Driven by my love/hate relationship with having to write some of the Greek letters during my Mathematics degree I decided to task myself with trying to classify some images of handwritten Greek letters that are most commonly used in mathematics. The images of these letters are a subset of a larger dataset known as HASYv2 courtesy of 'Thoma, Martin. "The hasyv2 dataset." arXiv preprint arXiv:1701.08380 (2017)' and is composed of nearly 170,000 32x32 black and white images of 369 different mathematical symbols and characters. The subset that I worked with in this project, 38 different letters (complete list shown on slide 4 of presentation), is composed of a variety of lower case, upper case and variant (different ways to write the same Greek letter) letters which can be seen in the image to the right. There are 31,520 such images. To see examples of these images I refer you to my project presentation, slide 6, that is also present on this repository. This slide also highlights some of the key challenges with this dataset, mainly images from different classes can look very similar. This could be due to mislabeling, but its mostly due to the handwritting of the letters and the close nature of some of the letters such as epsilon and varepsilon.


### Methods
In this project I tried using a variety of classification models such as SVM, Decision Trees, Random Forest and Convolutional Neural Networks(CNNs) to classify these 31,520 images. CNNs showed the most promise for this task and so the majority of this project is dedicated to working with them.

### Conclusions:
To evaluate the performance of the final model that I selected, a Convolutional Neural Network, I used 5-fold cross validation and obtained a mean accuracy result of 0.878. Additionally I also created my own images by handwritting the 38 different Greek letters used in this project and evaluated the final model's performance on these images. The model correctly classified 29/38 (76.3%) images correctly. Note that the image above is actually composed of my handwritten letters.

### Further Work
Due to time constraints I did not have enough time to do as much testing as I wanted to and the results I obtained can most certainly be improved. One appraoch that I did not have time to explore fully was image augmentation to increase the number of images the CNNs could work with. At the end of the workbook you will find a section that introduces this concept and showcases its potential by using Keras to perform a variety of image augmentations(rotations,zooms,shears,...). With more time to find the most suitable augmentations this may improve the results. 

---

This repository consists of the project notebook and presentation. 

As mentioned above, the dataset used in this project can be located using the paper: 'Thoma, Martin. "The hasyv2 dataset." arXiv preprint arXiv:1701.08380 (2017)'. The file is a tar.bz2 file and I have left code at the top of the workbook that will extract the files for you. (CODE WILL BE ADDED IN THE NEXT DAY as of 15/02/2022)
