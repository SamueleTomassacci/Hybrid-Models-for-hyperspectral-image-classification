# Hybrid-Models-for-hyperspectral-image-classification

This repository contains the code, trained models, and presentation materials for the Neural Network project.

***Repository Structure***

The repository is organized as follows:


* Models/
* Notebook_Hybrid Models for Hyperspectral Image Classification.ipynb
* Slides.pptx
* README.md
* pavia-university-hsi.zip

***Files and Folders Description***

*Models/*  
This folder contains the trained models with their saved weights after training.
Since the training process is relatively fast, these models are provided mainly for convenience and reproducibility; in fact the notebook is set to repeat the training each time it is launched.

*Notebook_Hybrid Models for Hyperspectral Image Classification.ipynb*  
This is the main Jupyter Notebook containing all the code of the project.
To correctly visualize it, in particular way the images present in th markdown cells, the notebook should be downloaded and imported on Kaggle, through the specific option "Import Notebook" after clicking on the icon "Create".

*Slides.pptx*  
PowerPoint presentation

*README.md*  
Project documentation and usage instructions.

*pavia-university-hsi.zip*  
This zip file contains inside the dataset used in the notebook


***How to View and Run the Code***

To correctly visualize the notebook (especially the embedded images in the markdown cells):
* Download the notebook file from this repository.
* Go to Kaggle.
* Create a new notebook and select Import Notebook (there is the icon "Create" and then "Import Notebook").
* Upload the downloaded .ipynb file.

***Dataset***

The project uses the Pavia University Hyperspectral Dataset, available on Kaggle:

Dataset link:
https://www.kaggle.com/datasets/syamkakarla/pavia-university-hsi

To add the dataset to the notebook:

* In Kaggle, open the notebook.
* Click on Add Input.
* Search dataset called pavia-university-hsi and add it.

Alternatively, as mentioned before, this repository contains a ZIP file with the dataset inside. Therefore, it can be downloaded and uploaded into the notebook; however, the first approach—using Kaggle directly—is better and faster.

***Running the Notebook***

To run the code correctly:

* Enable GPU (P100) in the Kaggle notebook settings.
* Run all cells sequentially from top to bottom.


Notes

The notebook is designed to be fully self-contained once the dataset is added.

No additional configuration or external dependencies are required beyond the Kaggle environment.
