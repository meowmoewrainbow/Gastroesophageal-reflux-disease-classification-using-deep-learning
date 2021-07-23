# Gastroesophageal-reflux-disease-classification-using-deep-learning
Transfer learning with ResNet50 as based model.

The model classify edoscopic images into 2 grades of gastroesophageal reflux disease: Grade A and Grade B

## Dataset
Private dataset from Hanoi Medical University Hospital. For privacy statement, I cannot public this dataset

Because of data scarcity, I used both offline and online data augmentation to create more data

## Result
                  precision    recall  f1-score   support

               0       0.86      0.76      0.81        25
               1       0.79      0.88      0.83        25

        accuracy                           0.82        50
       macro avg       0.82      0.82      0.82        50
    weighted avg       0.82      0.82      0.82        50
