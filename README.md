# Chest-X-ray-abnormality-detection
ARTIFICIAL INTELLIGENCE ASSESSMENT FOR OBJECT DETECTION OF CHEST ABNORMALITIES

The project uses YOLOv8 an object detection pre-trained model to analyse a dataset containing data about chest abnormalities found by several radiologists. A subset of the original dataset is used to train the model for testing it on a test dataset. The project uses a Jupyter notebook interface to pre-process the dataset and a Kaggle notebook interface to train the YOLOv8 model with the code written in Python programming language.

## Table of Contents
	•	Installation
	•	Usage
	•	Credits


## Installation
To install Jupyter notebook:
1. Download the latest version of Python from the official Python website: https://www.python.org/downloads/
2. Install pip in your terminal or command prompt by following the instructions in https://pip.pypa.io/en/stable/installation/ after checking whether you have installed pip by using the command ‘pip - - version’ in your terminal or command prompt.
3. Install Jupyter notebook using the command ‘pip install jupyter’ in your terminal or command prompt.
4. Launch Jupyter notebook using the command ‘jupyter notebook’ in your terminal or command prompt. The Jupyter notebook will get opened in your default web browser.
5. Open the pre-processing jupyter notebook used in this project from the file menu

## To open a Kaggle notebook:
1. Open the official Kaggle website: https://www.kaggle.com/
2. Create a gaggle account if you do not own one.
3. Click on the create notebook option in the menu.
4. Once a new notebook is opened, import the Kaggle notebook used in this project from the menu option - Import notebook

## Usage
1. Download the dataset from the link: https://www.kaggle.com/c/vinbigdata-chest-xray-abnormalities-detection/overview
2. Once you have downloaded the dataset, store it an appropriate file location.
3. Open the python jupyter notebook and run the jupyter notebook after modifying dicom images folder path, png images folder path, Training, Testing and Validation images and labels folder path. The training dataset folder and validation dataset folder must contain two folders each - named ‘images’ and ‘labels’. Incorrect spelling leads to the model not starting to train on kaggle. The test dataset folder should only contain one folder - ‘images’.
4. Upload the train, test and validations folders after compressing it onto kaggle data directory after importing the kaggle notebook from this project
5. Create a .yaml file consisting of the kaggle training images path, kaggle validation images path, number of classifications and the classes. Upload it onto kaggle.
6. Run the first two command lines of the kaggle notebook after any modifications you wish to do in the CLI. After running the first two commands, replace the model with the best model obtained after training the model from command two in the third command line, then execute command line three.

## Credits
This project was created by Cibhi Boopathy

