# Detecting COVID-19 from X-Ray

Data:
Pneumonia and Normal X_ray data: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia and
Covid X_ray data: https://github.com/ieee8023/covid-chestxray-dataset

Here, VGG16 is used with transfer learning

Model Accuracy:
classification report

                    precision    recall  f1-score   support

    Covid-19           1.00      1.00      1.00        30
      Normal           0.94      1.00      0.97        50
    Pneumonia          1.00      0.94      0.97        50

    accuracy                               0.98       130
    macro avg          0.98      0.98      0.98       130
    weighted avg       0.98      0.98      0.98       130

