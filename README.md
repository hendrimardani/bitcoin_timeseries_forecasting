# Description
This project implements advanced deep learning modeling for time series forecasting using an LSTM Sequence-to-Sequence (Seq2Seq) architecture. Unlike standard forecasting models, which can only predict a single future time point (single-step forecast), this custom model is designed using an Encoder-Decoder approach. This allows the model to “read” a complex series of past data (via the Encoder), understand its temporal context, and then “generate” a series of predictions for several steps ahead at once (multi-step forecast) via the Decoder.

### Model Performance Differences
<img width="691" height="756" alt="image" src="https://github.com/user-attachments/assets/adb89f6a-db68-493d-b694-ca5231a3d49c" />

### Visualization Model Performance Differences
<img width="1017" height="576" alt="image" src="https://github.com/user-attachments/assets/c1a2b640-e570-4994-923e-2a26d1a95642" />
