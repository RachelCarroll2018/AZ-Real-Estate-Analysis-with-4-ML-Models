# Project 2: Predictive Analysis on the Housing Market in Phoenix, AZ

## Group Members: Rachel, Sahaj, Jacob, Matt

Link to Google Colab: Prophet Model and LSTM RNN (File too big to upload):
[Link](https://colab.research.google.com/drive/1KYfv4rt8DAN4Gtgi-I5mTuW4YKsuHQ4c#scrollTo=YfW8kEQjBZtN) <br>
Arima: [Arima](https://colab.research.google.com/drive/1xSdrH6eaLHs9hKnD2Sun7dxveKmrl3-b#scrollTo=P9f-oitEJolt)

Slide Deck: [Powerpoint Slides](https://docs.google.com/presentation/d/1nvsEghoy8ITVGwbddee6Mjo9Xul0EkJ1yCKQl0QnyNc/edit#slide=id.g35f391192_00)

##  GOAL:
To create and compare prediction models using Prophet, Arima, Neural Network and LTSM RNN with housing data in Phoenix Arizona over the last 18 months.


## TECHNOLOGIES USED: 
Pandas, Stats models, Arima, PndArima, Tensorflow, Keras, Sklearn, Holoviews, Hvplot, Prophet, Numpy, Matploblib, Lexbot, Lambda.


## ROADMAP / STRATEGY:
- Find, clean and explore data
- Using Prophet, Arima, LSTM RNN, and Neural Networking for Predictive Analysis
- Analyzed results, changed window sizes, hidden layer features, added dropouts to create better results
- Analyzed results through graphs and MSE
- Finalize which model performed best


## PROPHET MODEL
![PROPHET 1](https://user-images.githubusercontent.com/100533905/176335696-3d42a554-6ebb-4c3b-a23f-37b4ad181023.png)
![PROPHET 2](https://user-images.githubusercontent.com/100533905/176335718-27bb6cfa-e94c-44ad-8e37-b52bb237dcc0.png)


## ARIMA MODEL
![ARIMA 1](https://user-images.githubusercontent.com/100533905/176335837-14dc5a94-81dc-4862-8edb-6d06e9f55946.png)



## NEURAL NETWORK
![NN 1](https://user-images.githubusercontent.com/100533905/176335931-9f6ed979-92a3-458d-bb9e-82220a599df7.png)
![NN 2](https://user-images.githubusercontent.com/100533905/176336041-7c7be945-0295-4697-a815-07974bf1b19b.png)
![NN 3](https://user-images.githubusercontent.com/100533905/176336069-d5716c65-0de5-486d-94a6-c7aabce7b776.png)


## LSTM RNN
![LSTM 1](https://user-images.githubusercontent.com/100533905/176336103-f15128f0-db36-453e-bfab-5a8740c602c3.png)
![LSTM 2](https://user-images.githubusercontent.com/100533905/176336112-88bd4a47-e53e-43d1-b0ab-06609ab7f1e9.png)



##  Which model shows the best predictability and least error?
Neural Network. This model had the best Mean Squared Error (.0001) and R2 Score (.945) of all models and followed the housing pricing closely. 


##  What do the models show about the housing market in 3 months?.
It overall depends on the area / ammenities but overall the market has increased in volume and demand which has lead to an increase in pricing as well.


## Additional Questions about Project from our Group?
1) What other models could perform better than what we used? 

2) Could the models we have be tweaked even further to be better

3) Are there any large scale examples of our project? What did they do differently?
