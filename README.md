


## Project Overview

Convolutional Neural Networks (CNN) project that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, it will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  



Goal is to understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.


## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/iNinad/dog-breed-classifier
		cd dog-breed-classifier
	```
	
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```
6. You can find the project proposal and the final report as .pdf files namely proposal.pdf and report.pdf in this repository.
7. Additional images are available in the added_images directory.
