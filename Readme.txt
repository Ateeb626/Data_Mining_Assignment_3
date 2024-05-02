This assignment performs anomaly detection on the PSM dataset from walmart
The dataset contained 24 features, Nulls were filled using the average of the columns.
I first simply did anomaly detection using 4 different models which included the PCA, Kmeans, an autoencoder and angled base outlier detection.
The accuracy and plots were drawn for each of the models and kmeans performed the best.
After that I augmented the dataset using the masked techniques in the paper and retrained the autoencoder improving its accuracy from 60 to 66
Now i retrained the autoencoder again using the contrastive loss function instead of the mean squared loss function, however the accuracy remained the same
