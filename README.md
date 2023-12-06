# MoodGuard-Training
 This repository contains a link to the compiled image dataset created for the MoodGuard chrome extension, as well as the jupyter notebook used for creating the model.

# Images
The final images used for this dataset were compiled from two pre-existing datasets you can find below:
1. https://data.world/crowdflower/image-sentiment-polarity
2. https://www.kaggle.com/datasets/varpit94/disaster-images-dataset

The final compiled dataset can be found through my dropbox:
https://www.dropbox.com/scl/fi/fuhcqlvzq5u6w6stp5993/moodguard_dataset.zip?rlkey=263796j5mkk30zpb73ibeb2ye&dl=0

# How do I use this?
Ensure the ```images``` and ```negative_aug``` folders are moved into the same directory as the ```Training_Notebook.ipynb``` and ```negative_aug.csv``` files before attempting to train your model. You will need to install Jupyter Notebook in order to run the code, found here: https://jupyter.org/. Once you've successfully installed Jupyter Notebook, use your terminal to navigate to the directory containing the dataset and the notebook and type ```jupyter notebook``` to launch Jupyter Notebook. From here, simply click on the ```Training_Notebook.ipynb``` and you're good to go!
