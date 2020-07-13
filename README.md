# Detecting COVID-19 & Pneumonia from X-Ray

Here, VGG16 is used with transfer learning


Data:

Pneumonia and Normal X_ray data: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia and
Covid X_ray data: https://github.com/ieee8023/covid-chestxray-dataset


Confusion_matrix:

![confusion_matrix](https://user-images.githubusercontent.com/68200424/87255856-fb224400-c4ab-11ea-8776-a8c761a5853a.png)

Model Accuracy:
classification report

                    precision    recall  f1-score   support

    Covid-19           1.00      1.00      1.00        30
      Normal           0.94      1.00      0.97        50
    Pneumonia          1.00      0.94      0.97        50

    accuracy                               0.98       130
    macro avg          0.98      0.98      0.98       130
    weighted avg       0.98      0.98      0.98       130

