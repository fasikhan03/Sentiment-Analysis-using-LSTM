## Code Instructions

1. Install all the requirements by running the cell below "Imports" or using pip
-the necessary requirements are:
    + numpy
    + pandas
    + tensorflow
    + sklearn


2. Use the IMDB dataset csv by changing the path for the read_csv function

3. Hyper-parameters for the best model are:
    + token-length = 200
    + num_words = 10000
    + max_length = 200
    + Embedding input_dim = 10000
    + Embedding output-dim = 128
    + LSTM units = 64
    + LSTM return_sequence = false
    + Dense activation = 'sigmoid'
    + Dense units = 1
    + epochs = 5
    + optimizer = 'adamax'
    + loss = 'binary_crossentropy'
    + metrics = 'accuracy'
    
4. Run the "Text cleaning and Pre-processing" and "Building and Training the LSTM model" with above mentioned values

5. Run the last cell "Evaluation" to calculate the f-score of the model

