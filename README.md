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

Model   | RNN | LSTM |   GRU-CNN | BD-LSTM |   BD-CNN*
F1 Score   | 93.02 | 94.24 |   94.72 | 95.43 |   95.61

*Model Results are from Sequential Convolutional Neural Networks for Slot Filling in Spoken Language Understanding, Ngoc Thang. Vu. and hasn't been evaluated in the code. 





