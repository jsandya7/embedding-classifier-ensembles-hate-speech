# Evaluating Embedding–Classifier Architectures & Heterogeneous Ensembles for Hate-Speech Detection

> **Summary**: This repo compares shallow & contextual **embedding–classifier** pipelines and builds **heterogeneous ensembles** across EDOS, Davidson, and HateXplain datasets. In experiments, ensembles delivered **~+10% macro-F1** over single models and showed stronger **cross-domain generalisation**.

---

## Project Scope
- Benchmark **embedding→classifier** pairs (TF-IDF→LR/SVM/XGB, GloVe→CNN/BiLSTM/MLP, BERT-family→CNN/BiLSTM/MLP).  
- Build **ensembles** (soft/weighted voting, stacking) across best-per-family models.  
- Evaluate **in-domain** and **cross-domain** generalisation.  
- Perform **detailed error analysis**:  
  - Group errors by model agreement/disagreement.  
  - Highlight implicit hate (sarcasm, humour, coded terms).  
  - Provide insights into model weaknesses and complementarity.  
- Provide training/evaluation pipelines, configs, and reproducible results.

**Content warning**: Datasets contain hateful/offensive text, used strictly for research.

## Contact
For more details, please contact:
- **Sandya Jalesh Kumar** – sandyajk7@gmail.com  
- **Ashwanth Sathish** – ashwanthx9@gmail.com  
