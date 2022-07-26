# next_word_prediction_LSTM_for_Bangla_PyTorch
Here I trained an LSTM coded for bangla next word prediction using LSTM. The .txt file used to train the LSTM is uploaded in this github repo. As this was coded in PyTorch custom model class needed to be created using model subclassing from the torch.nn.Module. The model.py script contains the model class. I also created a custom dataloader by defining a Dataset class that inherited torch.utils.data.Dataset, the codes for this class are inside the dataset.py script. To train the LSTM the train.py script was prepared which contains a custom training loop which uses the Model class from model.py and the Dataset class from dataset.py.





