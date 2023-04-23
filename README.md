# Random Forest Multiclass Model Covid-19

In this case study, I will use Random Forest to understand the scope of the Coronavirus using data from December and January of 2020. We want to predict the state of patient. I will predict if they are released from the hospital, isolated or deceased from the virus.

## 1. Explore the Data
- State of Patient:
- isolated    1791
- released     307
- deceased      32
- I have an imbalanced data set. Many of the patients are in isolation compared to the other two states of the patient's health.
## 2. Data Wrangling

- What to do with missing values? Mode & Mean

## 3. Visualizations of the Data

- Heatmap of the all the variables for the Covid 19 Data from South Korea

![image](https://user-images.githubusercontent.com/86930309/227577622-16fb17a2-51cc-4ed5-8023-65425deac72f.png)

- Global Number and Birth year plays a big part in thr random forest classifer model.

![image](https://user-images.githubusercontent.com/86930309/227578092-6c20fdea-72a3-409e-adbd-7e8b7b1a064d.png)

## 4. Random Forest Modeling

- Train/Test Split
- Acuracy & F1 Score:
- Random Forest: Accuracy=0.865
- Random Forest: f1-score=0.832
- Our model was very good at predicting if a patient was released.

![image](https://user-images.githubusercontent.com/86930309/227742304-e59d322a-ec48-4199-a89e-e1639e8ad453.png)

## 5. Summary

 In this case study we demonstrate the performance ability even with only a few features and almost all of them being highly correlated with each other. Our Random Forest Model predicted 86.5% of the patient's state correctly.
