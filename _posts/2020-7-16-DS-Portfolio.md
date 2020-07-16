---
layout: post
title: Data Science Portfolio
---

A sampling of data science projects I've worked on, recently.

#### Feli Gentle, [Data Scientist, Machine Learning Engineer](https://github.com/oro13)

### Project 1. [Machine Learning Enhancements for Learning Language App](https://github.com/oro13/language-app-ml)


I’m helping enhance the prototype with advanced Machine Learning components. Including, natural language processing of user generated content and a recommender of lessons based on user interests.

#### Data Pipeline Overview

My Research has centered on the most important app use case of uploading a lesson and recommending it to users if their activity implies it'd be relevent to them.

In general, a Recommender Needs these Three Steps:

1. item candidate generation
2. user specific scoring of items
3. reranking, or sorting the items based on relevance to the user

![app-prototype](/images/ds-portfolio/app_prototype.gif)


*The User logins in, uploads a lesson, and gets a recommended feed.*

![lda visualizer](/images/ds-portfolio/pylda_vis.gif)
*Using LDA to tag the user uploaded lessons with latent topic ids.*

Find out more about the project and research [here](https://github.com/oro13/language-app-ml)

---

### Project 2. Soil Health Prediction for Handheld Infrared Application

<img alt='working with the soil' src='https://raw.githubusercontent.com/oro13/soil-health-prediction/master/img/Micro_catchment.jpg' width='50%' height='50%'>

[photo by Malherbe Rossouw, South Africa ](https://commons.wikimedia.org/w/index.php?curid=63653257)

Soil health is our health. Here we hope to improve our tools of assessing soil health and make it widely available.

Infrared spectroscopy has traditionally provided great scientific insight. Now it can improve the quality of life of farmers and their ecosystems.

#### Infrared Spectroscopy: An Overview

*Infering nutrients through Infrared Spectroscopy*

Thousands of soil samples have been both scanned with (dry testing) and tested in the lab (wet testing), for a more complete soil profile. The goal is to predict the more detailed nutrient profile by using the coarser, but more efficient and affordable, infrared methods.

## Nutrient Predictions

On the left, you can find the wavelengths important for that specific nutrient model and on the right, the error plot of the predicted values.

#### Calcium
<img alt='infrared spectra' src='https://raw.githubusercontent.com/oro13/soil-health-prediction/master/img/final_ca1.png' width='35%' height='35%' align=left>
<img alt='infrared spectra' src='https://raw.githubusercontent.com/oro13/soil-health-prediction/master/img/final_ca2.png' width='35%' height='35%' alight=right>

#### Soil pH

<img alt='infrared spectra' src='https://raw.githubusercontent.com/oro13/soil-health-prediction/master/img/final_ph1.png' width='35%' height='35%' align=left>
<img alt='infrared spectra' src='https://raw.githubusercontent.com/oro13/soil-health-prediction/master/img/final_ph2.png' width='35%' height='35%' alight=right>
