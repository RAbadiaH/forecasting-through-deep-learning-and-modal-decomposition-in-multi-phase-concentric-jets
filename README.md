# forecasting-through-deep-learning-and-modal-decomposition-in-multi-phase-concentric-jets
Code of the paper: "Forecasting through deep learning and modal decomposition in multi-phase concentric jets"

This repository contains the code and dataset files for the paper: "Forecasting through deep learning and modal decomposition in multi-phase concentric jets", L. Mata, R. Abadia-Heredia, M. Lopez-Martin, J.M. Perez and S. Le Clainche. https://arxiv.org/abs/2212.12731.

The description of the different files is as follows:

- Normal_MONO_sim.mat: Data set corresponding to the simulation of the single-phase flow, without HODMD. In the paper this data set is referenced as S1.
- Normal_STS_sim.mat: Data set corresponding to the simulation of the two-phase flow problem without surface tension and with the simple geometry (spatial mesh with no bluff body). In the paper this data set is referenced as S2.
- rnn_model.ipynb: It provides an implementation of the RNN model for the datasets mentioned above. We encorage to use the link to the Google Colab notebook that can be find inside the file. In this way the entire notebook can be run, loading data sets, training the model and plotting the predictions.
