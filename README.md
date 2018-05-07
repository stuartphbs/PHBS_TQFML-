# PHBS_TQFML-Project
# Proposal
## Xu Wensong
## 1.	Project Description
This project is use the training set containing 28736 images of fruits to train classification models(SVM, RandomForest and KNN) , and use these models to recognize and classify the test fruit images. Finanly, by training differnet models, we could find the most promosing model.

## 2.	dataset propoerties:
<br>There are abundant high-quality imagines about 60 kinds of fruits containing Apples, Apricot, Avocado, Avocado ripe, Banana, etc. These imagines are filmed by a Logitech C920 camera and each imagine has a white sheet as backgroud. 

<br>Here is an example image of the dataset

<img src="https://github.com/stuartphbs/PHBS_TQFML-/blob/master/example%20image.png" width="450" height="300" alt="Example Image"/>


<br>More details about the dataset:
<br>Training set size: 28736 images.
<br>Validation set size: 9673 images.
<br>Number of classes: 60 (fruits).

<br> Data resource: Kaggle
<br> Data size: 180Mb

## 3.	Motivation,goal
  Because of the development of machine learning, image recognition technology has been widely used in life, so the task is to train the model through a set of fruit picture data, so that the model can recognize the kind of fruit.
  
## 4.	Result and conclusion
After several decompressing steps, I obtained training_data_pca. I trained SVM model, random forest and KNN, and used these models to classify test_images. The result showed KNN had the best performance on predicting, while SVM had the worst performance. More detail information are as below:
<br> Under SVM model,
<br>Average precision: 0.98
<br>Average recall:0.47
<br>Average f1-score:0.60
<br>
<br>Under RandomForest,
<br>Average precision: 0.88
<br>Average recall:0.87
<br>Average f1-score:0.86
<br>
<br>Under RandomForest,
<br>Average precision: 0.93
<br>Average recall:0.93
<br>Average f1-score:0.93



