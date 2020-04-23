# Results

Both Logistic Regression and SVC models were use to train the exoplanet data. The results find that the SVM model has an 88% testing accuracy while the Logistic Regression model's accuracy is 87%.

The Logistic Regression and the SVC model both had high recall and percision for all predicited values meaning that a majority of the predicitions are accuarate and are positivley confirmed. 

At the same time both models did have high precision for False Positive results meaning that the prediction was that it was not an exoplanet when it actually was an exoplanet. This precision being 0.98 for both the SVC and Logistic Regression models with a recall rate of 1. From my understadning this means that these tests are incorrect when predicting whether or not a hidden planet is a new exoplanet.

One would think that these models are missing information and are incorrectly predicting results. In this instance all of the False Positive results are confirmed meaning that the model is predicting that the result is the opposite of the actual result. In my opinion, the easiest way to correct this mistake is to identify and switch all of the False Positive results to display the opposite result of the False Positive report.