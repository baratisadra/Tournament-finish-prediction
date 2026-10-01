# NCAA Women's Basketball Tournament Finish Prediction

This machine learning project is made using **K-Nearest Neighbors (KNN)**  in  **R** to predict how far a team will advance in the NCAA Division I Women's Basketball Tournament.

## Overview

The project asks:

**Can a team's tournament seed and total win percentage be used to predict its tournament finish?**

Using historical NCAA Women's Basketball Tournament data from **1982–2018**, I built a classification model using:

- Tournament seed
- Total win percentage

as predictors of tournament finish.

## Model

The analysis used a **K-Nearest Neighbors classification model**.

The workflow included:

- 75% training / 25% testing split
- Standardization of predictors
- 5-fold cross-validation
- Tuning different values of `k`
- Final model using **k = 27**
- Evaluation using accuracy and a confusion matrix

## Results

The final model achieved approximately:

### **57% test accuracy**

The results suggest that **seed and win percentage provide useful information about tournament performance, but are not enough on their own to reliably predict exactly how far a team will advance.**

## Skills used in this project

- R
- Jupyter Notebook
- tidyverse
- tidymodels
- ggplot2
- kknn
  
## Future Improvements

The model could be expanded by including additional predictors, such as **conference**, to investigate whether they improve prediction accuracy.
