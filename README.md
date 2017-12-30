# Movie-Recommender

ENVIRONMENT SETUP:

	LOCAL SYSTEM:
		1. Mac OSX
				RAM 8GB 
				Intel i5 1.6GHZ
				python2.7

		2. Windows
				RAM 16GB
				Intel i5 2.5GHZ
				python2.7 and python 3.5

	AWS:
		Compute Optimized t2.xlarge
		RAM 16GB
		Speed 2.3 GHz
		4 vCPU
		variable ECU
		python 3.5
		pyspark


Data provided is almost clean, with very little need to preprocess, which was done in the ipython notebooks preprocessing.ipynb and cleaning.ipynb

STEPS:

	1. Data preprocessing
	2. Data cleaning
	3. Data Exploration and Visualization
	4. Before executing the machine learning models, data should be present in the specified S3 locations.
	5. Movie_Recommender_Baseline.ipynb predicts result using the baseline technique
	6. For improved prediction results using collaborative filtering, use Movie+Recommendation+ALS.ipynb


ACCURACY MEASURE :

	1. To measure the model accuracy, we computed f1 score, precision, recall and RMSE of the predictions
