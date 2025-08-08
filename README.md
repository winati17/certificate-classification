# Certificate Classification

**Description**  
This project aims to classify certificates based on text data, using text mining techniques on OCR outputs from certificate images.  
All analysis is conducted in a Jupyter Notebook.

---

## Project Structure
- `OCR2022.csv`, `OCR2023.csv`, `OCR2024.csv`  
  → OCR results from certificates in 2022, 2023, and 2024.

- `rawOcr.csv`, `rawOcr_filtered.csv`  
  → Raw and filtered versions of the OCR data.

- `label.csv`, `label_filtered.csv`  
  → Class labels before and after filtering.

- `Text-Mining.ipynb`  
  → Main notebook for text preprocessing, feature extraction, and classification.

---

## Main Features
The notebook workflow includes:
1. **Data loading** – reading and merging CSV files.
2. **Text preprocessing** – cleaning text, tokenization, stopword removal, and normalization.
3. **Feature extraction** – using TF-IDF or bag-of-words.
4. **Classification models** – such as Logistic Regression, Naive Bayes, or others.
5. **Evaluation** – measuring accuracy, precision, recall, and F1-score.
6. **Experiments** – comparing raw vs. filtered datasets to observe performance differences.

---

## Installation & Environment Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/winati17/certificate-classification.git
   cd certificate-classification
   ```

2. (Optional, but recommended) Create a virtual environment:
   ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
   ```

3. Open `Text-Mining.ipynb` in Jupyter Notebook. Follow the cell order:
- Load and explore the data.
- Apply preprocessing and feature engineering.
- Build and evaluate classification models.
- Compare performance using raw vs. filtered datasets.