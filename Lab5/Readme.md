Lab5: Recommender systems

Tasks:
1. Load the data from ``jester-data-1.csv''
2. Separate 10% of the dataset cells as as validation set.
3. Use latent factor modeling to infer the hidden ratings of the users
4. Calculate the performance (e.g., MSE) of the algorithm on the validation dataset
5. Repeat the two points above changing hyper-parameters (i.e., learning rate, number of iterations of SVD, number of latent factors, etc.) as needed to get good results (you can create multiple validation sets if you want, and run a bootstrap!)
   Once you're happy, make predictions for the test dataset
6. Use pandas to find the best- and the worst-rated jokes
