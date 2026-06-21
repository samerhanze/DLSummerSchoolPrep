# Deep Learning Summer School - June 2026

A hands-on, one-notebook-per-day course taking students from "what is a neuron?" to a complete,
portfolio-ready anomaly detection project.

## The Week at a Glance

| Day | Folder | Theme |
|---|---|---|
| 1 | `Day 1 - Neural Network Foundations` | What if you could teach a computer to think? Biology → artificial neurons → your first network from scratch in PyTorch. Theory meets code, from day one. |
| 2 | `Day 2 - Training, Tuning and Debugging` | What separates a decent model from a great one isn't magic; it's methodical tuning. Hyperparameter space, reading loss curves like a story, debugging models that refuse to converge. |
| 3 | `Day 3 - Convolutional Neural Networks` | CNNs don't just process pixels; they understand them. Convolution, pooling, CIFAR-10, transfer learning, object detection and face recognition. |
| 4 | `Day 4 - Sequence Models RNNs and LSTMs` | The world is full of sequences: speech, sensors, time series, text. RNNs and LSTMs model the fourth dimension. |
| 5 | `Day 5 - Capstone Anomaly Detection` | The final challenge: finding patterns no one explicitly taught the model to recognise. An LSTM-autoencoder anomaly detection pipeline — a project students can actually show off. |

Each day folder contains:

- **One main notebook** (`Day_N_*.ipynb`) — the day's full teaching content, ending with a recap,
  exercises and a teaser for the next day. The equivalent (`Day_N_*.executed.ipynb`) contains the same but with outputs for each cell.
- Supporting **images** referenced by the notebook (keep them next to the notebook)
- An **`extras/`** folder with optional deep-dive notebooks where relevant

## Extras Map

| Location | Notebook | What it's for |
|---|---|---|
| Day 1 | `extras/Tensors.ipynb` | Full deep dive into PyTorch tensors |
| Day 1 | `extras/activations.ipynb` | Side-by-side activation function comparison |
| Day 3 | `extras/convolution_output_dimensions_test.ipynb` | Layer-by-layer conv/pool output sizes |
| Day 4 | `extras/lstm_output_dimensions_test.ipynb` | Layer-by-layer stacked-LSTM dimensions |
| Day 5 | `extras/LSTM_AE_Hanoi_reference.ipynb` | The original Hanoi water-network study (its `Scenario-*.csv` data files are distributed separately) |
| Day 5 | `extras/conv_lstm_output_dimensions_test.ipynb` | Conv + LSTM hybrid autoencoder dimensions |
