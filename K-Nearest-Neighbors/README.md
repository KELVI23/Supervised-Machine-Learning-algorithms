# Segment-Customer-Base

 Use telecommunication provider data to segment customer base by service usage patterns and categorize them into 4 groups. If demographic data can be used to predict group membership, the company can customize offers for individual prospective customers.

### About the dataset 
 Will focus on using demographic data, such as region, age, and marital, to predict usage patterns.
 The target field, called custcat, has four possible values that correspond to the four customer groups, as follows: 1- Basic Service 2- E-Service 3- Plus Service 4- Total Service

<p align="left">
  <img src="https://imgur.com/2ooA5lt.png" alt="Dataset section" />
</p>

#### Process
1. Data preprocessing - normalize data
2. Train/Test split
3. Pick a random value of K and Test for accuracy
4. Evaluate the model for the best value of K

## Evaluation
 
 To choose the right value for K in KNN, you can reserve a part of your data for testing the accuracy of the model.
 Then choose k = random value/1, use the training part for modeling, and calculate the accuracy of prediction using all samples in your test set. Repeat this process, increasing the k, and see which k is the best for your model.
 
 #### Calculate the accuracy of KNN for different values of k.
<p align="right">
  <img src="https://imgur.com/bFM0hFA.png" alt="Number of neighbors plot" />
  </p>

 ##### The best accuracy was with 0.34 with k= 9