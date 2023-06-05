# Building a Text Message Spam Detector

In this project, we will build a text message spam detector using a dataset of messages already classified by humans as either spam or not. We will use two methods to classify new messages as spam or not: Naive Bayes and Logistic Regression. 

The [Naive Bayes algorithm](https://towardsdatascience.com/naive-bayes-classifier-81d512f50a7c), which will will build from scratch, will analyze text messages by determining whether the words in the message appeared more often in spam messages or non-spam messages. It is called Naive Bayes because the algorithm does not try to interpret how any word in a message is being used - it only looks for what words are present in the message.

The [Logistic Regression](https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc) model will also use training data that consists of messages that are already labeled as spam or not to create a Sigmoid function that will determine if any given message is likely to be spam or not. Logistic Regression is often used when a dataset needs to be classified into two or more categories (such as spam or not spam).

Some of the messages in our dataset contain adult content.
