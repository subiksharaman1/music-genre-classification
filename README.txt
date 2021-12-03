In this project, we build neural networks to classify the GTZAN dataset,
which was obtained from (http://marsyas.info/downloads/datasets.html). The GTZAN dataset
is a widely used dataset collected from 2000 to 2001 from multiple sources. The original
dataset consisted of 1000 audio tracks, spanning 30 seconds each, with 10 different
genres in total. For this project, we used a pre-processed dataset
where these audio tracks have been processed into features.

The pre-processed CSV file containing the features was obtained from
https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification. The 30-second-long audio files consist of 57 features
engineered by the dataset owner. The aim is to predict the genre of the corresponding audio files in the test dataset after
training the neural network on the training dataset. The genres are blues, classical, country,
disco, hip-hop, jazz, metal, pop, reggae and rock. Each data sample is a row of 60 columns,
which consist of filename (where you can find the original audio file if you like), length of
audio, label, and the 57 features which you will use.