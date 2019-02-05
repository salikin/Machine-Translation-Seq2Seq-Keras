# Topic Modelling using Latent Drichlet Allocation (LDA)

<p align="center"><img src="images/hello.jpg" height = "256"></p>

This is my implementation of English to French machine translation using seq2seq model in Keras.
Due to limited computing power of AWS free tier EC2 instance, I used a dataset of small vocabulary size (200~300 words).


At the end, the model was able to perfectly translate from an english sentence to a french sentence within the supplemented vocabulary.


## Repository 

This repository contains:
* **data/** folder : contains english and french sentences dataset files 
* **machine_translation_seq2seq.py** : Complete code for building, training, and making inference from seq2seq model in Keras
* **machine_translation_seq2seq.ipynb** : step-by-step Jupyter Notebook for for building, training, and making inference from seq2seq model in Keras



## List of Hyperparameters Used:

* Batch Size = **1024**
* Embedding Dimension = **200**
* Number of hidden nodes in LSTM = **256**
* Activation Function for encoder & decoder LSTM layer = **ReLU**
* Learning Rate = **0.002*
* Number of Epochs = **16



## Sources

I referenced the following sources for building & debugging the final model :

* https://nextjournal.com/gkoehler/machine-translation-seq2seq-cpu
* https://machinelearningmastery.com/define-encoder-decoder-sequence-sequence-model-neural-machine-translation-keras/
* https://blog.keras.io/a-ten-minute-introduction-to-sequence-to-sequence-learning-in-keras.html
* Udacity's Natural Language Processing Nanodegree's workspace

