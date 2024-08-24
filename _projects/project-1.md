---
title: "Meitu Users Age Stage Prediction Model"
excerpt: "<div style='width: 600px;'>
  <div style='text-align: justify;'> 
    This project mainly used machine learning and deep learning models to predict the age stage of Meitu users. 
  </div>
  <div style='text-align: left;'>
    <img src='/images/agestage_predict.png' style='width: 600px; height: auto; display: block;' alt='meitu membership user'>
  </div>
</div>"
collection: projects
---

<p class="page__date">
  <strong>
    <i class="fa fa-fw fa-calendar" aria-hidden="true"></i> 
    Date:
  </strong> 
  <time datetime="2024-08-05">
    August 5, 2024
  </time>
</p>

<img src='/images/agestage_predict.png' style='width: 800px; height: auto;'>

<p style="text-align: justify;">This project mainly used machine learning and deep learning models to predict the age stage of Meitu users.</p>


<p style="text-align: justify;">The goals of this project were to enhance the accuracy of age stage prediction and expand the coverage of the users' age stage labels. The project primarily developed three versions of the model, employing the following methods:</p>


<p style="text-align: justify;">(1) Established Logistic Regression and Random Forest models to predict the age stages of Meitu users based on users’ portrait labels, community consumption behaviors, tool click behaviors, and other features, achieving an initial accuracy of 45% and then implemented a stacking model of Logistic Regression, Random Forest, and XGBoost, which increased the model accuracy to 50%.</p>


<p style="text-align: justify;">(2) Segmented the words, filtered out special characters and stop words, calculated the TF-IDF value to vectorize the features based on the text information of users in the Meitu user-generated content community, used the chi-square test for feature selection, and established a Spark MLP model to predict the age stage of Meitu users and the model accuracy was 52%.</p>


<p style="text-align: justify;">(3) Established a decision tree model to predict the age stage of Meitu users based on the users’ portrait labels, community consumption behaviors, tool click behaviors, and other features, with a model accuracy of 60% and added the users’ date type preference and users’ time segment preference based on the previous features to establish a LightGBM model, with the model accuracy increased from 60% to 66%.</p>


<p style="text-align: justify;">In the end, the models predicted the age stage of hundreds of millions of Meitu users, with the accuracy rate increasing from 45% to 66%.</p>

