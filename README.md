# Predicting Hotel Booking Cancellations

The purpose of this project is to predict whether an advanced booking at a hotel will be cancelled by training classification algorithms on a set features to choose between two classes in the target feature (1 for cancelled and 0 for not cancelled). Cancellations can lead to a loss in revenue for hotels making it a worthwhile endeavour to predict whether a given booking is likley to cancel. 

Five classifiers (three base, two ensemble algorithms) all from different categories are initially tested. Based on the scoring, one base and one ensemble algorithm will be fine-tuned and tested on a subset of data set aside to simulate future, unseen data. Due to the heavy presence of categorical features in this dataset, this project places equal emphasis on data preprocessing as it does with the predictive modelling component.

### Contents

<ul>
  <li>1. Exploratory Data Analysis   
    <ul>
      <li>1.1 Data Characterisitcs</li>
      <li>1.2 Target Feature
      <li>1.3 Data Visualization</li>
      <li>1.4 Correlation</li>
     </ul>
   </li>
   <li>2. Data Preparation and Transformation Pipelines   
     <ul>
      <li>2.1 Splitting the Data</li>
      <li>2.2 Create Custom Transformers</li>
      <li>2.3 Construct Pipeline</li>
     </ul>   
   </li>
   <li>3. Model Selection</li>
   <li>4. Hyperparameter Fine-Tuning   
     <ul>
      <li>4.1 K-Nearest Neighbors</li>
      <li>4.2 Random Forest</li>
      <li>4.3 Evaluation and Comparision of Final Models</li>
     </ul>   
   </li>
   <li>5. Deploying Model on "Real-World" Data</li>
</ul>

This dataset can be found on <a href="https://www.kaggle.com/jessemostipak/hotel-booking-demand">Kaggle</a>, and as per the uploader, "the data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019."
