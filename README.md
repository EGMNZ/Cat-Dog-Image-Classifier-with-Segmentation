<b>Image Segmentation</b>
<br>
This project is a part of the AAI-521 course in the Applied Artificial Intelligence Program at the
University of San Diego (USD). 
-- Project Status: Completed

<img width="391" alt="imgSeg" src="https://user-images.githubusercontent.com/105265021/206610278-73d69681-5f71-455a-8794-8de7f0e8b625.png">


<b>Prerequisites</b>
* ```Google Drive``` (https://www.google.com/drive/)
* ```Google Colab``` (https://colab.research.google.com)
  - You can run individual cells in google colab by pressing ```shift + enter``` or you run all the cells by going to ```Runtime``` and then hitting ```Run all```.
* Create/Register for a ```kaggle accounnt```. You can register for an account here (https://www.kaggle.com/account/login?phase=emailRegister)

<b>Installation</b>
<br>
In order to run the code you will need the ```train.zip``` and ```test1.zip``` files which are provided in the repository. You may also obtain these files from https://www.kaggle.com/competitions/dogs-vs-cats/data. We need to put these files in our working directory inside our ```Google Drive```. Once we have those files added to our ```Google Drive``` then we can open up ```Google Colab```. Open the ```AAI_521_Group3.ipynb file``` inside google colab. Run the first cell to import the required python modules. Run the second cell to mount your google drive you may be asked for permission to connect to your drive. If so allow google colab to connect so that it may access the files need to continue running the rest of the code. After this run the rest of the cells in order. If you would like to change the specific image to test the image segmentation portion on you can update the variable ```file``` which is in the second cell of the *Classifying An Unseen Image Using Best Performing Model section*.

<b>Note:</b> Your path may be different than ours so you will have to update the path in a few sections. 
Once the path has been updated you should be able to run the rest of the cells in the in the file. 

<b>Project Objective</b>
<br>
The main purpose of this project is demonstrate our ability to create a machine learning model that takes in the images, classifies them, and lastly use the grabcut algorithm to perform image segmentation. The goal of this project is to have a model that can take in a dataset of images and accurately classify those images. In our case we used a dataset that consists of dog and cat images. We also want to to be able to perform image segmentation on these images.

We can potentially use this to make profiles for animals, people, or other things. An example would be pet profiles at a animal shelter. They could use this to classify an animal and then take their photo (after image segmentation has been performed) and create a nice profile with it. Vets can also use this to make profiles for their animal patients.



<b>Partner(s)/Contributor(s)</b>
* Alejandro Monje: alejandromonje@sandiego.edu
* Edgar Munoz: edgarmunoz@sandiego.edu
* Xavier Plasencia: xplasencia@sandiego.edu  


<b>Methods Used</b>
* Exploratory Data Analysis 
* Computer Vision
* Machine Learning
* Data Visualization
* Deep Learning (Convolutional Neural Networks) 
* Pre-Trained VGG16 model 
* GrabCut algorithm


<b>Technologies</b>
* Python
* Jupyter Notebook/Google Colab

We chose to use a kaggle dataset on cats and dogs (https://www.kaggle.com/competitions/dogs-vs-cats). Our data set comes from Kaggle (https://www.kaggle.com/competitions/dogs-vs-cats/data). It contains a total of 25,000 images. It’s equally split between cat (12,500) and dog (12,500) images. The images in the dataset vary in size and we can see the distribution of sizes in the image below. 

GNU General Public License v3.0

Image classification and image segmentation can be used in many different fields. How we can apply these skills and tools can have a huge impacts on our society. We asked ourselves what we can do with these tools and stumbled across the daogs and cats dataset. Our goal is to use EDA inorder to gain isights into our data and visualize what we find using bar charts and scatterplots. We are going take advantage of deep learning Convolutional Neural Networks of the pre-trained VGG16 model for classification and The GrabCut algorithm for the image segmentation portion. An issue we had to tackle was images of various sizes. We overcame this problem through normialization and scaling the data. We ultimately were able to achieve our goal of classifying images and performing image segmentation.
 
Special thanks to our professor (Roozbeh Sadeghian, Ph.D.) who answered questions and helped clear up any confusion with the assignment.

