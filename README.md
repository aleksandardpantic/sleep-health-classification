# Sleep Health Classification

## Features

+ ***Gender***: The gender of the person (Male/Female).
+ ***Age***: The age of the person in years.
+ ***Occupation***: The occupation or profession of the person.
+ ***Sleep Duration (hours)***: The number of hours the person sleeps per day.
+ ***Quality of Sleep (scale: 1-10)***: A subjective rating of the quality of sleep, ranging from 1 to 10.
+ ***Physical Activity Level (minutes/day)***: The number of minutes the person engages in physical activity daily.
+ ***Stress Level (scale: 1-10)***: A subjective rating of the stress level experienced by the person, ranging from 1 to 10.
+ ***BMI Category***: The BMI category of the person (e.g., Underweight, Normal, Overweight).
+ ***Systolic Blood Pressure***: The blood pressure measurement of the person (upper value)
+ ***Diastolic Blood Pressure***: The blood pressure measurement of the person (lower value)
+ ***Heart Rate (bpm)***: The resting heart rate of the person in beats per minute.
+ ***Daily Steps***: The number of steps the person takes per day.
+ ***Sleep Disorder(target)***: The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).

***Using deep learning on 12 predictors, predicting Sleeping Disorder variable.***

## Metrics

Categorical Cross-Entropy and Categorical Accuracy 

## Results

On unseen data, model predicts correctly in approx. `93.3%` of cases with Categorical Cross-Entropy loss of `0.39`

## Note

Model was built using Keras and scikit-learn libraries.<br>
Model was tuned by Grid Search from keras-tuner library.<br>
_Pipeline objects are saved as binary files in `data-pipelines-bin/` directory._
_Model was saved as `results/model.keras` and visualized in `model/model.png`._
_Model training history was saved as `results/history-tuned.csv` and final evaluation as `results/evaluation.csv`._
