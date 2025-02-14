### RNN Word Prediction Using Custom Dataset
### Overview:
This project aims to predict the next word in a sentence using a Recurrent Neural Network (RNN). The process involves manually defining a dataset, followed by tokenization, numeric encoding, and creating features and targets. An embedding layer is added before the RNN to represent words in dense vectors, improving prediction accuracy. The model is trained to predict the next word, achieving an accuracy of approximately 86%.

#### Steps:
1. Data Preprocessing:
Manually create a dataset, tokenize sentences, and perform numeric encoding.

2. Feature and Target Creation:
Use a sliding window approach to define features (input words) and targets (next words).

3. Embedding Layer:
Add an embedding layer to convert words into dense vectors for better word representation.

4. RNN Model:
Construct an RNN with an embedding layer, an RNN layer, and a dense output layer.

5. Training and Prediction:
Compile the model, train it, and use it to predict the next word in the sequence.

6. Results:
The model achieves an accuracy of around 86% in predicting the next word.
