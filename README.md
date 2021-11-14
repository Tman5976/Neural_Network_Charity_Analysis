# Neural_Network_Charity_Analysis

## Purpose

Our challenge was to create a model that could predict the successful outcome for a charity if funded by Alphabet Soup. We accomplished this by creating a neural network group of neural network models to try and find a reliable model.

## Results

- Data Preprocessing
		
	- The IS_SUCCESSFUL column was the target for our model.
	
	- The following columns were the features for our model:
		- APPLICATION_TYPE
        - AFFILIATION
        - CLASSIFICATION
        - USE_CASSE
        - ORGANIZATION
        - STATUS
        - INCOME_AMT
        - SPECIAL_CONSIDERATIONS
        - ASK-AMT

	- EIN and NAME columns were removed from the data.

- Compiling, Training, and Evaluating
	- In the final model:
	    - Four layers with 9,011 parameters with a Relu activation function.
        The target module performance was not achieved.

	- Performance improvement steps.
		- Extra hidden layer
        - Adding number of neurons
        - Increasing cutoff for AT_COUNTS bucket to 1000.

## Summary

The accuracy of our different models were all too low to be considered reliable. The models were between 53-54% at predicting the accuracy of the models.
I think a model that shows the importance of the different features would help improve the accuracy. There may be features in the current model that could be left out of future models to help improve performance.