# Breast_Cancer_Classificaton_RF
## Steps

### 1. import Libraries 

### 2. Load Dataset 

### 3. Data Pre-Processing 

### 4. Split the data

### 5. Train The Random Forest Classification Model

### 6. Evaluate the Performance
- With default parameter
- prediction on test data


                ****** prediction on test data *******
                Confusion Matrix
                [[88  3]
                [ 2 47]]
                ---------------------------------------------------
                Classification Report
                            precision    recall  f1-score   support

                        0       0.98      0.97      0.97        91
                        1       0.94      0.96      0.95        49

                 accuracy                           0.96       140
                macro avg       0.96      0.96      0.96       140
                weighted avg    0.96      0.96      0.96       140

- prediction on train data

                ****** prediction on train data *******
                Confusion Matrix
                [[367   0]
                [  0 192]]
                ---------------------------------------------------
                Classification Report
                            precision    recall  f1-score   support

                        0       1.00      1.00      1.00       367
                        1       1.00      1.00      1.00       192

                 accuracy                           1.00       559
                macro avg       1.00      1.00      1.00       559
                weighted avg    1.00      1.00      1.00       559


- With different parameters
- prediction on test data

                ****** prediction on test data *******
                Confusion Matrix
                [[87  4]
                [ 1 48]]
                ---------------------------------------------------
                Classification Report
                            precision    recall  f1-score   support

                        0       0.99      0.96      0.97        91
                        1       0.92      0.98      0.95        49

                accuracy                            0.96       140
                macro avg       0.96      0.97      0.96       140
                weighted avg    0.97      0.96      0.96       140


- prediction on train data

                ****** prediction on train data *******
                Confusion Matrix
                [[360   7]
                [  0 192]]
                ---------------------------------------------------
                Classification Report
                            precision    recall  f1-score   support

                        0       1.00      0.98      0.99       367
                        1       0.96      1.00      0.98       192

                 accuracy                           0.99       559
                macro avg       0.98      0.99      0.99       559
                weighted avg    0.99      0.99      0.99       559


### 7. Pickling of Model
 
### 8. Model Deployment on render
1. README file
2. requirements.txt
3. app.py
4. style.css
5. main.html
6. Dockerfile
7. main.yaml

### 9. Deploy on Render