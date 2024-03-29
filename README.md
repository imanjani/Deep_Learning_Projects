# Deep Learning Projects


#### 1 - Fraud Detection with Self Organizing Map (SOM)
I've used credit Approval dataset to detect some potential fraudsters with the help of a Self Organizing Map using the 'minisom' package. 

<img src="/Fraud_Detection_SOM/som.png" width="30%"/>

---

### 2  Fake News Classifier Using Bidirectional LSTM

<img src="https://user-images.githubusercontent.com/68546391/97145655-91912180-178c-11eb-925d-1347dca903ff.jpg" width="40%"/>


**### LONG SHORT- TERM MEMORY (LSTM)**<br/>
LSTM is a recurrent neural network (RNN) architecture that REMEMBERS values over arbitrary intervals. LSTM is well-suited to classify, process and predict time series given time lags of unknown duration. Relative insensitivity to gap length gives an advantage to LSTM over alternative RNNs, hidden Markov models and other sequence learning methods.

![LSTM1](https://user-images.githubusercontent.com/68546391/97147145-0b2a0f00-178f-11eb-9562-05553182afb9.png)

Math Behind it : https://colah.github.io/posts/2015-08-Understanding-LSTMs/

**### Bi-directional LSTM**<br/>
![Bidirect](https://user-images.githubusercontent.com/68546391/97147474-94414600-178f-11eb-9952-78bc76c8e2e7.png)

Bidirectional LSTMs are an extension of traditional LSTMs that can improve model performance on sequence classification problems.
In problems where all timesteps of the input sequence are available, Bidirectional LSTMs train two instead of one LSTMs on the input sequence. The first on the input sequence as-is and the second on a reversed copy of the input sequence. This can provide additional context to the network and result in faster and even fuller learning on the problem.

---
### 3 LSTM RNN for text generation with Keras

	- here we will split the book text up into subsequences with a fixed length of 100 characters, an arbitrary length 
	- LSTM layers with 300 memory units
	- used dropout at 20
	- output layer is dense layer using softmax activation
	- we are modeling the training dataset to learn the probability of each chracter in dataset
	- there is no testing dataset
	- network is slow to train, so we would use checkpoints to record all network weights to a file each time an improvement is observed
---

#### 4 - Predicting Google Stock Price with RNN model

Used an [LSTM neural network](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) to predict the closing price of Google stock using Yahoo stock API. This model can be used to predict the stock of any company. Just replace the company name in the code

<img src="/stockPricePrediction.jpg" width="50%"/>


---
#### 4 - Handwritten Digit Classification with CNN


<img src="/mnist.png" width="50%"/>



