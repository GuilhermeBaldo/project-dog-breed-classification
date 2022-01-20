## Project Overview

This project consists of using convolutional neural networks (CNNs) to produce an algorithm composed of a pipeline of CNNs. That algorithm identifies if an image provided by the user contains a person, a dog or neither. In the case of a dog, the algorithm responds with the dog breed. In the case of a person the algorithm responds with the dog breed the person in the picture most resembles. Finally in the case of neither a dog nor a person in the image the algorithm will respond with invalid input. 

![project overview](images/diagram.png?raw=true)

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/GuilhermeBaldo/project-dog-breed-classification.git
		cd project-dog-breed-classification
	```
	
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `dogImages/`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `lfw/`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Create the conda environemnt usint the environment.yml file.

	```	
		conda env create --file=environment.yaml
	```

5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```