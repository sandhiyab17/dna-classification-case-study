# DNA Classification Using Machine Learning & Feature Extraction

A machine learning project comparing algorithms (CNN, DNN, N-gram) with and without feature extraction (3-gram, Levenshtein Distance) for DNA sequence classification across viral datasets.

---

##  Project Overview
Genomic sequence classification is crucial for bioinformatics and viral diagnostic applications. This project evaluates how traditional feature extraction techniques perform compared to deep neural networks learning directly from raw DNA sequences.

###  Datasets Used
- **COVID-19:** SARS-CoV-2 DNA/RNA sequences
- **AIDS:** HIV Type 1 vs. Type 2 sequences
- **Influenza:** Various flu strain sequences
- **Hepatitis C:** Virus-specific genomic sequences

---

##  Feature Extraction & Models

### Feature Extraction
- **3-Gram:** Generates overlapping triplets representing nucleotide patterns and amino acids.
- **Levenshtein Distance:** Calculates sequence edit distance against sub-sequences to quantify similarity.

### Machine Learning Models
- **CNN (Convolutional Neural Network):** Learns representations directly from raw DNA sequences.
- **DNN (Deep Neural Network):** Fully connected network trained on extracted feature vectors.
- **N-Gram Model:** Probabilistic classifier for sequence pattern matching.

---

##  Tech Stack & Requirements

- **Language:** Python 3.x
- **Libraries:**
  - `numpy` & `pandas` (Data processing)
  - `scikit-learn` (Metrics & N-gram classification)
  - `tensorflow` / `keras` (CNN & DNN implementation)
  - `Levenshtein` (Edit distance computation)

---

##  Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/sandhiyab17/dna-classification.git](https://github.com/your-username/dna-classification.git)
cd dna-classification


pip install numpy pandas scikit-learn tensorflow Levenshtein
python main.py

Models were evaluated using standard classification metrics across all datasets:

Accuracy, Precision, Recall, and F1-Score

Key Findings:
3-Gram Feature Extraction: Showed the strongest overall performance on larger viral datasets.

Levenshtein Distance: Produced the best accuracy on the COVID-19 dataset.

CNNs & DNNs: Learned effectively directly from raw sequences without requiring manual feature engineering.

** References**
Paper: Zhang, X. et al. (2020). Comparing Machine Learning Algorithms with or without Feature Extraction for DNA Classification. arXiv:2011.00485

https://arxiv.org/abs/2011.00485
<img width="917" height="123" alt="image" src="https://github.com/user-attachments/assets/27bfa1db-772d-4d1e-bfdd-4260ba309a79" />


















