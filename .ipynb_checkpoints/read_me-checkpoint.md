# Project Classification

The first notebook to open is the data notebook. That in conjunction with the locations notebook were used to scrape data from PG&E reports as well as collect data from Dark Sky and Google Maps APIs. The data from the locations notebook was uploaded to Postgresql and then queried into the data notebook. The dataframe at the end of data collection and cleaning is pickled as model_data.

The mvp notebook is a very quick go at a logistic regression model on the data. It establishes a baseline for the models in the modeling notebook.

The modeling notebook contains the code for oversampling, modeling, and visualization.