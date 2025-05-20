# DA6401-Assignment-3
# Sequence-to-Sequence Learning with Recurrent Neural Networks

## 📘 Overview

This project explores the application of Recurrent Neural Networks (RNNs) to sequence-to-sequence (seq2seq) learning problems. Through this assignment, we aim to understand and compare the functionality of different recurrent units, as well as enhance the basic seq2seq model using attention mechanisms.


##  Goals

1. **Modeling Sequence-to-Sequence Learning**
   - Implement encoder-decoder architecture using RNNs for tasks such as transliteration.
   
2. **Cell Comparison: Vanilla RNN, LSTM, GRU**
   - Compare model performance using different RNN variants.
   - Evaluate learning capacity, convergence, and generalization.

3. **Attention Mechanism**
   - Implement attention to overcome the limitations of standard encoder-decoder models.
   - Improve performance on longer or complex input sequences.

4. **Visualization**
   - Visualize attention weights and internal representations of RNN models.
   - Understand how different components interact during training and inference.

## Experiments

- Train and evaluate models using different recurrent cells.
- Conduct ablation studies to evaluate the impact of:
  - Attention mechanism
  - Teacher forcing
  - Cell type and number of layers

##  Visualization

- Plot training and validation losses.
- Visualize attention weights for qualitative analysis of model performance.
- Track experiments using Weights & Biases (wandb).

---

## 📁 Structure
Files:
vanilla_sweep_train.ipynb
attn_rnn_sweep_train.ipynb
attention_predictions.txt
vanilla_prediction.txt
