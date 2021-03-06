## **Project Objectives**

In this project, we build a neural network that predicts musical genres of audio files. We are essentially creating a genre classifier trained on the GTZAN dataset, which was obtained from (http://marsyas.info/downloads/datasets.html). 

## **Dataset**

The GTZAN dataset is a widely used dataset collected from 2000 to 2001 from multiple sources. The original dataset consisted of 1000 audio tracks, spanning 30 seconds each, with 10 different genres in total. For this project, we used a pre-processed dataset where these audio tracks have been processed into features. The pre-processed CSV file containing the features was obtained from https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification. The 30-second-long audio files consist of 57 features engineered by the dataset owner. The genres are blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae and rock. Each data sample is a row of 60 columns, which consist of filename, length of audio, label, and the 57 features used for genre classification.
