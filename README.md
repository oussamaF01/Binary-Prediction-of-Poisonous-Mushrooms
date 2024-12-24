# Playground Series - S4E8 Kaggle Competition 🧑‍💻🍄

This repository contains my solution to the [Playground Series - S4E8](https://www.kaggle.com/competitions/playground-series-s4e8) Kaggle competition. The goal of this competition is to predict whether mushrooms are poisonous or edible based on their features. 🌱

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Approach](#approach)
- [Results](#results)
- [License](#license)

## Overview 🌟
In this competition, we are tasked with predicting whether mushrooms are poisonous or edible. The dataset contains various features of mushrooms, such as cap shape, color, odor, habitat, and others, which help in classifying them. The objective is to build a model that can predict the correct classification with high accuracy.

## Dataset 📊
The dataset used in this notebook is provided by Kaggle and can be found [here](https://www.kaggle.com/competitions/playground-series-s4e8/data).

### Data Description 📑
- **class**: The target variable (edible or poisonous).
- **cap_shape**: Shape of the mushroom cap.
- **cap_surface**: Surface condition of the mushroom cap.
- **cap_color**: Color of the mushroom cap.
- **bruises**: Whether the mushroom has bruises.
- **odor**: Odor of the mushroom.
- **gill_attachment**: Attachment of the gills to the stem.
- **gill_spacing**: Spacing between the gills.
- **gill_size**: Size of the gills.
- **gill_color**: Color of the gills.
- **stalk_shape**: Shape of the mushroom stalk.
- **stalk_color**: Color of the stalk.

## Approach ⚙️
In this notebook, I explored the dataset and implemented several classification models. Here's a brief overview of my approach:
1. **Data Preprocessing**: 
    - I performed data cleaning and encoded categorical variables using label encoding.
    - Missing values (if any) were handled appropriately.
2. **Modeling**: 
    - I experimented with **XGBoost** 🏎️ and used **RandomizedSearchCV** 🔍 for hyperparameter tuning.
3. **Evaluation**: 
    - I evaluated the models based on accuracy and other relevant metrics.
    - The final model was selected based on the best performance on the validation set.

## Results 🏆
The final model achieved a score of **0.98275** on the competition leaderboard 🎯. I found that XGBoost with optimized hyperparameters outperformed other models in this classification task.

## License 📜
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
