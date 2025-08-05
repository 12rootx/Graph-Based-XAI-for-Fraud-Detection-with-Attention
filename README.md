# Graph-Based Explainable AI for Fraud Detection with Attention

![Fraud Detection](https://img.shields.io/badge/domain-fraud%20detection-blue)
![Graph Neural Networks](https://img.shields.io/badge/technique-GNNs-orange)
![XAI](https://img.shields.io/badge/approach-explainable%20AI-green)

This repository contains the implementation of a Graph Neural Network (GNN) with attention mechanism for fraud detection in banking transactions, developed as part of a research paper project.


## Project Overview

This repository contains the implementation of a Graph Attention Network (GAT) for interpretable fraud detection in financial transactions, developed as part of academic research. The model outperforms Graph Convolutional Networks (GCNs) and GraphSAGE baselines while providing visualization and attention-based explanations.


Key features:
- **Graph Construction**: Methods to transform tabular transaction data into meaningful Heterogeneous graph structures
- **Detection Performance**: GAT-based model leveraging attention mechanisms for improved accuracy
- **Explainability**: Attention mechanism and visualization for explainability
 
## Dataset

The dataset used is from Kaggle: [Transaction Data for Banking Operations](https://www.kaggle.com/datasets/ziya07/transaction-data-for-banking-operations).


## Technical Approach

The implementation follows these main steps:

1. **Environment Setup**: Configures Python libraries including PyTorch Geometric for GNNs
2. **Data Loading**: Loads and preprocesses transaction data
3. **Graph Construction**: Builds heterogeneous graphs
4. **Model Architecture**: Implements GNNs
5. **Training & Evaluation**: Includes Model training pipeline, Performance metrics (accuracy, F1, precision, recall)

Note: This implementation is part of academic research. Please cite appropriately if used in your work.
