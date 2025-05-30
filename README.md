# Contrastive Text Classification
Text classification using contrastive learning with Siamese, Triplet, SupCon, and SBERT-based models.


## 🧠 Techniques Used

- **Siamese Network**: Learns similarity between sentence pairs.
- **Triplet Network**: Uses anchor, positive, and negative samples to learn discriminative embeddings.
- **Supervised Contrastive Learning (SupCon)**: Learns better class-wise separation in embedding space.
- **SBERT (Sentence-BERT)**: Pre-trained transformer-based sentence embeddings for contrastive learning.

# 📦 Installation:
Install the required packages:


pip install transformers datasets sentence-transformers faiss-cpu torchmetrics


# 📚 Dataset:
The PAWS: labeled_final dataset is used, which contains pairs of sentences labeled as paraphrase (1) or not (0).


# 📈 Results:
All models report classification performance using precision, recall, F1-score, and confusion matrices for Siamese, while Triplet is evaluated based on embedding quality.

# 🧑‍💻Authors:

- Azka Qadir
- Roshni

# 📌 Disclaimer:
This project was developed as part of a personal learning journey in NLP. As such, it may include experimental implementations, non-optimized code, or areas for improvement. Feedback, suggestions, and contributions are always welcome!

