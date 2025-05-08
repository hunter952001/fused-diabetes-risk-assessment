# fused-diabetes-risk-assessment

Authors: @ajtomov01, @Ryder-Li, @hunter952001

Here we use a linear regression model trained on a CDC healthcare survey and a CNN trained on a diabetes retinography database for diabetes risk assessment. 

The script MLMA_FinalProject.ipynb downloads 253,680 responses to a CDC healthcare survey and uses it to train a linear regression model. Then, the script poses a survey for the user for diabetes risk assessment based on the trained model.

The script CNN_Attempt.ipynb downloads a diabetes retinography database and uses it to train a CNN model. 

The script Ensemble_Risk_Assessment.ipynb takes the f1-score from both of the prior models, takes a random sample from each dataset, and combines them to provide a fused diabetes assessment.
