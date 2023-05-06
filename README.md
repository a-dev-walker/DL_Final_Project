# DL_Final_Project
Deep learning final project. CNN for histopathology images


Github repository for the deep learning project "Deep Learning Histopathologic Metastasis Classification" by Adam Walker and Ryusei Miyanaga. 

The main script is "deep-learning-final-project_kaggle_notebook.ipynb." Beacuse the dataset that we used for this project was rather large, we utlized the built in jupyter notebook system on Kaggle for creating our models. To use this python notebook, you must first join the Kaggle project (https://www.kaggle.com/competitions/histopathologic-cancer-detection/overview) and create a new notebook under the code tab. From there you can upload this python notebook into the system. All of the data should be staged properly and the pip commands at the top of the script will add the necessary packages. 

As for the neptune integration, you will need to create a neptune project for this run and place the API key for that project in the location indicated in the code. I have left my API key in-line for now so that the code runs, but you will not be able to observe the output of the code without making your own neptune project and API key. 


The visualization portion of the code is in it's own python notebook labeled "Visualization_processing." All of the files required for this processing are included in this repository and the code should work as intended by simply running it. Please note that there is one code chunk in this script to rename input files. These files have already been renamed and thus this chunk can be commented out when recreating the processing. 