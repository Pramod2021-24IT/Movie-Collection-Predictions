# Movie-Collection-Predictions-

Movie Collection Prediction
This assignment will help you practice the concepts you are learning side-by-side.
Click here to download the Datasets.
This dataset contains data of movies, where our task is to predict the collection (revenue) the movie is going to make using variables such as expense, rating genre, etc. Please perform the following tasks
•	Import ‘Movie_collection’ csv files in data_x and data_y variables.
•	Look at the shape and first five rows of both dataframes to understand the data
•	Split the data into test, train, and validation
•	Take a look at the shape of the test, train, and validation set
•	Standardize the data
•	Create an ANN model with 2 dense layers of 30 neurons each
•	Compile the model with loss="mean_squared_error", optimizer=keras.optimizers.SGD(lr=1e-2) and metrics=['mae'])
•	Train the model for 100 epochs
•	Evaluate the model performance on the test set
•	Predict the values of the first 5 test records
