Digit Recognizer(Kaggle Challenge): In this challenge , the feature set include set of pixels.
Train set contain 785 columns of pixels which describe an digit image of 28x28 plus one number column.
Test set contain the set of pixel and id only.
The job is to create the model which predict the number by the pixel and create a result file have id and predict result .

Model used: Supervise Learning svc of sklearn svm and matplotlib for plotting and image viewing.
Links : https://github.com/rahulrksmau/digit-prediction
Datasets : https://www.kaggle.com/c/digit-recognizer/data

Steps done : feature engineering and data cleaning, model training, testing over train dataset, model accuracy, predicting the result for actual dataset at last creation of submission csv. 
Result : Above model having accuracy of 90.2%.
