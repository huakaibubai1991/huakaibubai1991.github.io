---
title: "Meitu User Age Stage Prediction Model"
excerpt: "<div style='width: 600px;'>
  <div style='text-align: justify;'> 
    This project mainly uses machine learning and deep learning models to predict the age stage of Meitu users. 
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

<p style="text-align: justify;">This project mainly uses machine learning and deep learning models to predict the age stage of Meitu users.</p>


<p style="text-align: justify;">The goal of this project is to improve the accuracy of age stage prediction and increase the coverage of user age stage label. This project mainly established three versions of the model, and the methods are as follows:</p>


<p style="text-align: justify;">(1) Established LR and random forest models to predict the age stage of Meitu users based on the users’portrait label, community consumption behavior, tool click behavior and other features, with a model accuracy of 45% and then established a stacking model of LR, random forest, and xgboost, and the model accuracy increased to 50%.</p>


<p style="text-align: justify;">(2) Segmented the words, filtered out special characters and stop words, calculated the TF-IDF value to vectorize the features based on the text information of users in the Xiuxiu community, used the chi-square test for feature selection, and established the Spark MLP model to predict the age stage of Meitu users and the model accuracy was 52%.</p>


<p style="text-align: justify;">(3) Established a decision tree model to predict the age stage of Meitu users based on the users’ portrait label, tool click behavior, community consumption behavior and other features, with a model accuracy of 60% and added the users’ date type preference and users’ time period preference based on the previous features to establish the lightgbm model, and the model accuracy was increased to 66%.</p>


<p style="text-align: justify;">In the end, the age stage of users at the billion level was predicted, and the model accuracy was increased from 45% to 66%.</p>

