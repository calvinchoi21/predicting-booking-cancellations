# Predicting Hotel Booking Cancellations

This project uses information entered by the customer at the time of booking to predict whether they will end up cancelling the booking. Several classification algorithms are trained on the dataset to build models that will assign one of two labels to each record, cancelled or not cancelled. 

- Dataset contains records on 119,390 bookings made between two hotels. Extensive EDA was conducted to determine preprocessing needs.
- Custom data transformers are built to automatically discretize, bin, and group specific features, as well as creating new features using existing data. 
- Off-the-shelf sklearn preprocessors are also used to impute missing values, encode categorical data, perform feature selection, etc. 
- Pipelines are constructed to bind together transformers and estimators for further automation. 
- Five classifiers are initially tested, and two were shortlisted (KNN and Random Forest) based on highest f1-score. 
- Used GridsearchCV on pipeline to tweak both estimator and transformer parameters to arrive at the strongest model.
- Code: [Link](https://github.com/calvinchoi21/predicting-booking-cancellations/blob/master/Predicting_cancellations.ipynb) 

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
