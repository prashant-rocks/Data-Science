# Spam Detection : Analysis and Modelling

Lets ANALYSE and Create the MODEL to predict SMS as ham/spam from SPAM data
![spam filter](https://github.com/prashant-rocks/Data-Science/blob/master/Machine%20Learning/Naive-Bayes-Multinomial-Classifier-Spam-Dataset/src/images/spam-detection.png)

## What we are analyzing and achieving
 1. We are analyzing the data within the spam-dataset through different preprocessing technique like: shape, info, description etc.
 2. We see data through different graphs like: histogram to see how data is behaving and if larger messages(length of data) are trending towards being spam.
 3. We will use bag-of-words technique to convert our text format (strings) data to numerical feature vector in order to perform the classification task.
 4. We will clean data after analysis as well as standardize the same to provide weightage accordingly.
 5. We will try to create model to eventually predict the class of message i.e. ham/spam.

## Data Analysis
1. We have total number of 5572 messages as research dataset.
2. We have ham/spam as 2 labels(classes) against messages data and 5169 unique messages.
3. Ham category messages are 4825 and one message has higher frequency as 30.
4. We have certainly duplicate messages as unique < count.
5. We don’t have any null valued data within the dataset.
6. As we have text messages and we need to visualize more to make a decision in message category, we create new column as “length”.
7. Plotting histogram against the column length, we see something which was not visible through text that length of the spam messages are usually high(mostly 130+) compared to legitimate messages.
8. They are trying to convince us anyhow.

## Conclusion
1. We have applied bag-of-words approach to convert text format to be usable for Naive Bayes(NB) classifier.
2. After evaluation through Classification report, we can fairly say that messages can be classified into ham/spam with good accuracy.
3. We can certainly achieve more fair accuracy with more data input to the model.

