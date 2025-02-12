# nba-players-facial-detector
This repository contains my Capstone project for Professional Certificate in Machine Learning &amp; Artificial Intelligence by Berkeley ExecEd/Berkeley Haas

## The context

As a fan of sport, I thought AI could have a real impact to help not initiated people to understand how the different sport
are working. It gave me the idea that if people could have clues on which players they are seeing on their screen, it could
help them understand the comments and what is happening, so it could bring more audience to sport and even reunited people
so people not watching sports could enjoy watching with the people they love that are into sports.

For this project I used data from kaggle from the repository: [here](https://www.kaggle.com/datasets/djjerrish/nba-player-image-dataset-201920),
30 players on the 450 have been used for this training for performances purposes, but it can be done using all the players, the results
will be very similar it will just need more time of processing.

## The results

In general the predictions have been very successful, for the project three models have been created using respectively:
Multi-Layer Perceptron, AdaBoost and RandomForest; each algorithm have been used for classification. The only model that
have not been satisfying with very low results around 13-14% on both the training and the test dataset is AdaBoost, on
the other side, Multi-Layer Perceptron and RandomForest have been very efficient, both have been able to reach 99% of
success on the training dataset and 100% on the testing dataset. Now long term I would tend to use more the RandomForest
since  the training of the data is 4 times faster than the Multi-Layer Perceptron, the data will rarely evolve and it
is a deterministic algorithm.


## The notebook

If you want to read the project, the notebook is accessible [here](https://github.com/jbbenoist/nba-players-facial-detector/blob/main/NBA%20Players%20Facial%20Recognition.ipynb).