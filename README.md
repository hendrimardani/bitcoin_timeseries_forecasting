# Description
This project implements advanced deep learning modeling for time series forecasting using an LSTM Sequence-to-Sequence (Seq2Seq) architecture. Unlike standard forecasting models, which can only predict a single future time point (single-step forecast), this custom model is designed using an Encoder-Decoder approach. This allows the model to “read” a complex series of past data (via the Encoder), understand its temporal context, and then “generate” a series of predictions for several steps ahead at once (multi-step forecast) via the Decoder.

