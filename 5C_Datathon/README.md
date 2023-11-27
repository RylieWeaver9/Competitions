# 5C Hack - Flight Delay Prediction Project

## Overview

This repository contains the work our team did for the '5C Hack' data science competition held at the Claremont colleges. As the team lead, I, Rylie Weaver ([RylieWeaver](https://github.com/RylieWeaver)), along with my teammates George Johnson ([tsawsum](https://github.com/tsawsum)) and Abraham Arias ([HonestlyAbe](https://github.com/HonestlyAbe)), guided our efforts in developing a binary classifier to predict flight delays.

## Project Description

The challenge was to create a model that accurately predicts whether a flight would be delayed, based on the dataset provided. The data had limited direct correlation to flight delays, making this a challenging and interesting problem.

## Our Approach

1. **Preliminary Analysis**: We started with an exploratory data analysis to understand the dataset's characteristics and potential challenges.

2. **Feature Engineering**: We crafted meaningful features from the dataset to enhance the model's predictive power.

3. **Data Balancing and Preprocessing**: Given the imbalanced nature of the dataset, we implemented data balancing techniques and thorough data preprocessing to prepare the data for effective modeling.

4. **Model Development**:
   - **Initial Linear Model**: Our first approach was a linear model, which provided mediocre results.
   - **Neural Network**: We then developed a neural network that significantly improved our predictions.
   - **Ensemble Approach**: The most effective model was an ensemble, where the linear model's predictions were used as an input to the neural network. This hybrid approach yielded our best results.

## Results

- Our final ensemble model achieved a **70.2% accuracy** in predicting flight delays.
- We closely competed with the top teams, with the first-place team achieving a 71.2% accuracy.

## Reflection

This competition was an excellent opportunity to apply various data science techniques in a real-world scenario. It also highlighted the importance of innovative approaches like ensemble modeling in solving complex problems.

---

For more details about our methodology, models, and analysis, please see the individual files within this directory.
