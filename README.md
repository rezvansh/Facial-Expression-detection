# Facial-Expression-detection

## Introduction
In this project, we want to classify images based on the facial expressions manifested in the images and label each image with an emoji among 10 emojis  "Slightly Smiling Face", "Slightly Frowning Face", "Fearful Face", "Confounded Face", "Face with Rolling Eyes", "Flushed Face", "Neutral Face", "Angry Face", "Winking Face with Tongue" and "Grimacing Face". 

## Dataset
I have created a custom dataset by mixing the images and facial expression labelling of the dataset of this project https://github.com/muxspace/facial_expressions with some pictures and their facial expression labelling I downloaded from Google Images. In the mentioned GitHub project, there is a dataset of 13,718 images with their labels in a CSV file. The emotions in the labels were "happiness", "sadness", "fear", "disgust", "contempt", "surprise", "neutral" and "anger". I have converted these expressions to the following emojis, respectively: "Slightly Smiling Face", "Slightly Frowning Face", "Fearful Face", "Confounded Face", "Face with Rolling Eyes", "Flushed Face", "Neutral Face" and "Angry Face". I have also downloaded images related to "Winking Face with Tongue" and "Grimacing Face" emojis then added them to the dataset. The final dataset includes 13,861 images that have each been labelled with an emoji among 10 emojis. 
## How to run the code
In order to run the code, download the Jupyter notebook file ("Facial\_expression\_detection.ipynb"), the folders "images" and "test" and the CSV file "gendata.csv". \textbf{Please make sure to change the paths in the code according to where you put "images" folder, "test" folder and "gendata.csv"}. Finally, run the cells in Jupyter starting from the 1st cell.
