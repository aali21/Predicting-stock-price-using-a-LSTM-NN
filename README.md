# Predicting-stock-price-using-a-LSTM-NN
**Note: The full project can be found in a pdf [here](https://drive.google.com/file/d/1MAm7GADYjwFu6rmf1gTYv2ED-k07_NgW/view?usp=sharing)**  
A program for predicting the stock price of any stock or index available on Yahoo Finance
* Cleaned and preprocessed the data, ready for input into the model
* Used StandardScaler() to standardize data
* Predicted the stock price of Facebook between 2017 and 2020 using a LSTM neural network (with the help of tensorflow and keras libraries)
* Found that increasing the number of epochs will overfit data causing test set accuracy to reduce
* An ideal number of iterations was found to be 250.
* Achieved a RMSE of 11.67

![standardized_FB_predictions](https://user-images.githubusercontent.com/29689235/117378458-602ca780-aecd-11eb-814b-3ce7f018c6fa.png)
The prediction of Facebook stock price with 250 iterations

![loss_FB_250](https://user-images.githubusercontent.com/29689235/117378545-98cc8100-aecd-11eb-8a4d-df7a3ca35fca.png)
