# Movie-poster-Genre-Prediction
We propose to achieve movie genre classification based only on movie poster images. A deep neural network is constructed to jointly describe visual appearance and object information, and classify a given movie poster image into genres. Because a movie may belong to multiple genres, this is a multi-label image classification problem. To facilitate related studies, we collect a large-scale movie poster dataset, associated with various metadata. 
# DATASET 
The dataset was collected from the IMDB website. One poster image was collected from one (mostly) Hollywood movie released from 1980 to 2015. Each poster image is associated with a movie as well as some metadata like ID, genres, and box office. The ID of each image is set as its file name.

## Total Poster Images-7254
## Total Genres -25 


# Testing the model on external files

![poster git 2](https://user-images.githubusercontent.com/67013985/93320904-3d129200-f82f-11ea-80c4-9ac4ee31a123.png)
![poster git 3](https://user-images.githubusercontent.com/67013985/93321838-48b28880-f830-11ea-8b8e-0cd3a022aed9.png)

# RESULTS

# ACCURACY-

# MODEL TRAINING  ACCURACY -91%
# MODEL VALIDATION ACCURACY-90%

# LOSS-

# TRAINING LOSS- 0.2453
# VALIDATION LOSS- 0.2579



# LIMITATIONS-
1.The main Problem  in Multi-label classification is data imbalance the 50% of the poster have Drama as one of its Genre because of this the Model is always predicting Drama as its one of the Genre. 

2.Subjective movie labelling by IMDb sources & varied posters for release.

3.Transfer learning proved to be of little value in this multi-label problem.Training with VGG16 model overfit the model after 32 epochs it gave accuracy of 56% and validation accuracy of 33% it clearly was overfitting the model.Better is to train CNN model.








