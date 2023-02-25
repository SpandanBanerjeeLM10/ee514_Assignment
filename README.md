# Data Analytics and Machine Learning (EE514) module assignment

Assignment aim : Behavioral context recognition in-the-wild from mobile sensors
Dataset credits : This dataset was collected in 2015-2016 by Yonatan Vaizman and Katherine Ellis with the supervision of professor Gert Lanckriet.
Department of Electrical and Computer Engineering, University of California, San Diego.
Original publication: "Recognizing Detailed Human Context In-the-Wild from Smartphones and Smartwatches". 

As part of this assignment, I learned :
- Load data from excel into Jupyter Notebooks
- Select features & target from the dataset
- Extract training data 
- Preprocess the data by making all columns have a mean of zero and a standard deviation of one, using imputation to get rid of missing values.
- Fitting a logistic regression model
- Using training accuracy to check the health of our selected model
- Test the model on unseen data by combining 5 random users and finding the accuracy in each case
- Generating a classification report to find f-score, precision, recall and support
- Plotting the ROC Curve
- Using different models like logistic regression with different c-parameter, SVC with two different kernels
