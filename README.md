# Next-Word-Prediction
Next Word Prediction Model enables our device to predict what could be the next word that we are planning to type.
We used LSTM to train the model, we will train our model by feeding it some data in text file (Pride and Prejudice by Jane Austen in our case), and If we type first 3 words in the program, it'll predict the next word from the same eBook it was trained from.
Libraries used in this code:
➢ TensorFlow: TensorFlow is a Python library for fast numerical computing created and released by Google.
➢ Keras[6]: Keras is an Open Source Neural Network library written in Python that runs on top of Tensorflow, we have used several modules of Keras such as text preprocessing, layers, models[9], utils, optimizers[11]
➢ Pickle[5]: Python pickle module is used for serializing and de-serializing python object structures. The process to converts any kind of python objects (list, dict, etc.) into byte streams (0s and 1s) is called pickling or serialization or flattening or marshalling. We can converts the byte stream (generated through pickling) back into python objects by a process called as unpickling.
➢ numpy: numpy is a library consisting of multidimensional array objects and a collection of routines for processing those arrays.
➢ os: The os path module is a very extensively used module that is handy when processing files from different places in the system
