# Proposal

## Design
For this project I'm classifying musics by genres. The dataset I'll be using is the GTZAN dataset where they have the 1000 sounds of music from 10 different categroies. The categories are **blues, classical, country, disco, hiphop, jazz, metal, pop, reggage, rock**. The features I will be measuring are **chroma shift, cens, mel spectrogram, mfccs, spectral centroid, spectral bandwidth, spectral contrast, spectral faltness, spectral rolloff, poly features, tonnetz, zero crossing rate**. 

## Data
The data is from GTZAN dataset downloaded at http://marsyas.info/downloads/datasets.html. They have 1000 music files in wav format for 30 sec and for each category there will be 100 music data each. With this data, I wanted to divide each music into partion of music by seconds so that I can compare if the model will trained better comparing 30, 15, 10, 5, 3 seconds music.

## Algorithm
Building multiple classification models to compare which model best fits on different size of datasets. The algorithms will solve multi-classification problem because there will be 10 different genres that are labeled in the dataset. Evaluation metrics are **accuracy, precision, sensitivity, specificity, negative predictive, and log loss**. Throughout the project, if there are better foundings in the metrics, I will include them as well.

## Tools
One of the main library I will be using for EDA is the **Librosa** library to extract information from the GTZAN dataset. Then will be using **sklearn** package to do most of the modeling and training data. For visualization, I will use **seaborn** and **matplotlib** to have graphs for analyze such as the **ROC curve**.
