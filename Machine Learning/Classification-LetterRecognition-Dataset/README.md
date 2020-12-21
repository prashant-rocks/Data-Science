# Letter Recognition : Analysis and Modelling
It's a multiclass classification problem with 26 classes.

Each row in the data set represents an image of a handwritten alphabet. Using image processing, images are converted into m X n pixels.

Using the pixelated images, 16 features are derived for each image, such as the width of the box, the ratio of the mean variance of x divided by the width of the box, etc.


## Data Analysis
 1. There are total 18 columns and having 16000 rows.
 2. We see that there is no missing/null values and so we don’t need to fill any values.
 3. We have all continuous columns except “letter”which is target variable and string in type.
 4. We have created barplot with columns x-box and letter.
 5. We see I has minimum value and W has maximum as you can see the bars.
 6. The above statement signifies the most simplistic ( A ) and most wide/complex( W ) design of alphabets.
 7. M has second largest value as it has similar design as W but less wide and different orientation.


## Modelling and Prediction

 1. We have applied 4 classification algos so as to compare which one is best.
 2. **Accuracy**:

		1.*Random Forest Classifier* : 96.125%

		2.*KNN* : 94.59%

		3.*XGBoost* : 83.69%

		4.*Support Vector Classifier* : 97.28%

We clearly see that RFC and SVM wins here as per accuracy score and we will apply our LetterRecognition Test Dataset with these two algorithms.
