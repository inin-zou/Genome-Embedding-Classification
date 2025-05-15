# 🚀 Phage Genome Embedding & Classification Hackathon Project

## 🧬 Overview

Bacteriophages (phages) are viruses that infect bacteria and play a crucial role in microbial ecology, biotechnology, and medicine. Rapid identification and classification of phages from genomic data is essential for applications such as:

- Phage therapy  
- Microbiome engineering  
- Pathogen control  
- Agricultural and environmental interventions

Our project focuses on developing an **AI-driven pipeline** that identifies and classifies bacteriophages **capable of infecting a specific bacterial host**, with an emphasis on *Pseudomonas syringae*. Leveraging Transformer-based genome embeddings, we aim to enable scalable and accurate phage-host prediction.

---

## 🎯 Project Objective

> Build a scalable AI pipeline that predicts potential bacteriophage candidates capable of infecting *Pseudomonas syringae* by analyzing genomic features.

This pipeline includes:

1. **Genome filtering** for relevant bacterial species  
2. **Embedding extraction** using pre-trained Transformer models (e.g., NucleotideTransformer and evo-1-8k-base)  
3. **Dimensionality reduction & batch correction**  
4. **Species-level classification** using embeddings  
5. **Unsupervised clustering** for insights into sub-species diversity  

---

## 💡 Why Is This Important?

### 🔬 Phage therapy as a solution to antibiotic resistance

- **Antibiotic resistance** is a growing global health crisis.  
- **Phages offer targeted, efficient alternatives**, especially effective against biofilm-forming or drug-resistant bacteria.

### 🌱 Precision microbiome and environmental applications

- **Host-specific targeting** allows for precise elimination of harmful bacteria while preserving beneficial ones.
- **Use cases beyond healthcare** include:
  - Crop protection in agriculture  
  - Food safety  
  - Environmental microbiome regulation  

---

## 🛠️ Tech Stack

- **Python**, PyTorch, scikit-learn, pandas, matplotlib
- **Transformer-based models**:
  - [`NucleotideTransformer`](https://huggingface.co/InstaDeepAI/nucleotide-transformer-v2-2.5b-multi-species)
  - [`evo-1-8k-base`](https://huggingface.co/nucleotide-transformers/evo-1-8k-base)
- **Dimensionality Reduction**: PCA, UMAP, t-SNE
- **Batch Effect Correction**: (e.g., ComBat or custom normalization)
- **Visualization**: seaborn, matplotlib
- **Clustering & Classification**: KMeans, Random Forests, Logistic Regression, etc.

---

## 🔮 Future Vision

- Expand to **multi-host prediction**, enabling broader phage-host matching.
- Integrate **functional annotations** (e.g., tail fiber proteins, CRISPR hits).
- Enable **interactive candidate ranking** based on infectivity potential.
- Evolve into a **phage-host AI platform** with cloud-based inference and automated genomic input processing.

---

## 👥 Team

- Yongkang ZOU
- Iyed JAZIRI
- Zhor KHADIR