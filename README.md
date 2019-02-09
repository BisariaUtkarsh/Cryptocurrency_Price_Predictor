# Cryptocurrency_Price_Predictor

RNN - model predicts the future price movement for four cryptocurrencies as follows :

<ul>
    <li><b>Bitcoin (BTC)</b></li>
    <li><b>Bitcoin Cash (BCH)</b></li> 
    <li><b>Litecoin (LTC)</b></li>
    <li><b>ETHEREUM (ETH)</b></li>
</ul>

We have access to data of aforementioned cryptocurrencies. Following approach is used to
preprocess the data :
<ul>
    <li>Normalize the data</li>
    <li>Scaling</li>
    <li>Creating Sequences of 60 minutes from data</li>
    <li>Balancing the data</li>
</ul>

Sequences created during preprocessing of data are further used in RNN model during 
training which helps to predict future price movement of next 3 minutes for each cryptocurrency.

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;


## Visualization of  In-sample & Out-sample Accuracy
![spit_safe](https://github.com/BisariaUtkarsh/Cryptocurrency_Price_Predictor/blob/master/insample_acc.png)

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;

![alt text](https://github.com/BisariaUtkarsh/Cryptocurrency_Price_Predictor/blob/master/insample_loss.png)

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;

![alt text](https://github.com/BisariaUtkarsh/Cryptocurrency_Price_Predictor/blob/master/outsample_acc.png)

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;

![alt text](https://github.com/BisariaUtkarsh/Cryptocurrency_Price_Predictor/blob/master/outsample_loss.png)
