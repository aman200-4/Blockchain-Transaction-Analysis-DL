# 🔗 Blockchain Transaction Analysis using Deep Learning

This project explores the use of deep learning techniques to analyze blockchain transaction data for anomaly or fraud detection. The solution integrates multiple models, including Graph Neural Networks (GNN), Autoencoders, and LSTMs, to detect patterns and outliers in transactional behavior.

### 🚀 Highlights
- Graph-based modeling with PyTorch Geometric
- Unsupervised anomaly detection using Autoencoder
- Sequential trend analysis with LSTM
- Custom dataset with structured blockchain features

---

## 📁 Dataset Overview

The dataset contains transaction-level data including:

- transaction_id, timestamp, from_address, to_address
- transaction_value, transaction_fee, gas_used, block_number, is_contract
- Graph features: in_degree, out_degree, degree_centrality
- Time-based features: txn_count_last_24h, time_diff_from_prev_txn
- Label: 0 = Normal, 1 = Anomaly

---

## 🧠 Models Used

- *Graph Neural Network (GNN)*: Captures structure and address-level interaction
- *Autoencoder*: Learns feature compression to highlight outliers
- *LSTM*: Understands transaction patterns over time

---

## 🔧 Tools & Libraries

- PyTorch, torch-geometric for deep learning and graph modeling
- Pandas, NumPy for data handling
- Scikit-learn for preprocessing
- Google Colab as development environment

---

## 📊 Results

- GNN Accuracy: coming soon  
- Autoencoder Loss & Anomaly Scores  
- LSTM Sequence Visuals  
- Graph-based insights from address interactions

---

## 👨‍💻 Author

*Aman Meena*  
Final Year B.Tech CSE | AI & ML Enthusiast  
🔗 Open to Internships | [GitHub](https://github.com/aman200-4)
