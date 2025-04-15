# 🎧 EchoNet: Federated Speech Evaluation Platform

A Federated Learning-based project that trains and evaluates **speech-to-text models** across decentralized clients. It computes **Loss**, **WER (Word Error Rate)**, and **BLEU score** per client and visualizes performance over multiple training rounds.

---

## 🚀 Features

- 📡 Federated training across multiple clients
- 🎙️ Evaluation on real speech-to-text data
- 📉 Metric computation per client:
  - Loss
  - Word Error Rate (WER)
  - BLEU Score
- 📊 Graphical visualization of performance metrics across training rounds
- ⚡ Optimized for GPU acceleration

---

## 📁 Project Structure

```bash
├── main.py              # Training + evaluation script
├── plots.ipynb          # Graphs and metrics visualizations
├── README.md            # You're here!
```

## Clone the repository

Copy

- git clone https://github.com/your-username/EchoNet.git
- Install dependencies

python main.py
Visualize results Open plots.ipynb in Jupyter to view performance graphs.

📊 Sample Graphs
Graphs generated during training:

📈 Average WER vs Rounds

📈 Average BLEU vs Rounds

📈 Per-Client Loss

You can find graphs and visuals under the plots.ipynb notebook or assets/ folder if generated.

🧠 Technologies Used
Python

PyTorch

Transformers (HuggingFace)

Federated Learning

Matplotlib & Seaborn for visualizations

📜 Dataset
The dataset is split across 10 clients to simulate decentralized learning.

Each client holds a unique subset of the speech-to-text data for federated evaluation.

🧑‍💻 Author
Nagarjun H
📫 nagarjunh77@gmail.com
🌐 GitHub: Nagarjun-07
