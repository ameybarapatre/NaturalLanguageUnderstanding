# Keras Models for ATIS Dataset
Spoken Language Understanding(SLU)/Slot Filling in Keras. 

There are 4 models created in Keras to solve the Airline Travel Information System(ATIS) dataset.

1. Simple RNN  
2. LSTM
3. CNN with GRUs to Capture Future Contexts
4. BiDirectional LSTM

Here is an example sentence and its labels from the dataset:

  Show   | flights | from |   Boston | to |  New | York|    today
  ---   | --- | --- |   --- | --- |  --- | ---|    ---
 O | O | O |B-dept | O|B-arr|I-arr|B-date


## Results

Model    | F1 Score
RNN      |  93.02
LSTM     |  94.24
GRU-CNN  |  94.72
BD-LSTM  |  95.43
BD-CNN*  |  95.61

*Model Results are from Sequential Convolutional Neural Networks for Slot Filling in Spoken Language Understanding, Ngoc Thang. Vu. and hasn't been evaluated in the code. 





