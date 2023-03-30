Problem 1 (60pts)

In this homework, we focus on the language model we did in the lectures.

Use the GRU example, adjust the hyperparameters (fully connected network and the number 
of hidden states) and analyze their influence on running time, perplexity, training and 
validation loss, and the output sequence (try a few examples).

Use the LSTM example, adjust the hyperparameters (fully connected network and the number 
of hidden states) and analyze their influence on running time, perplexity, training and 
validation loss, and the output sequence (try a few examples)

Compare runtime for training and inference, computational and mode size complexities, 
training and validation loss, and the output sequence (try a few examples)for rnn.RNN, 
rnn.LSTM and rnn.GRU implementations with each other use the same hyperparameters for 
your comparison. 
 


Problem 2 (40pts)

This homework focuses on the Deep RNN problem we did in the lectures.

Build the model by replacing the GRU with an LSTM and compare the training and validation 
loss, and the output sequence (try a few examples) against GRU.

Compare runtime for training and inference, computational and mode size complexities, and 
the output strings for nn.LSTM and rnn.GRU implementations with each other.

Adjust the hyperparameters (fully connected network, number of hidden layers, and the number
of hidden states) and compare your results (training and validation loss, computation 
complexity, model size, training and inference time, and the output sequence). Analyze their
influence on accuracy, running time, and computational perplexity.
