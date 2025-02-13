# NLP-Strategy-Comprehension

## Overview
This repository contains the Python scripts developed for the text mining and text analysis of academic literature in the field of "Made in Italy." The project employs advanced Natural Language Processing (NLP) techniques to extract and analyze key themes, terms, and concepts from a large corpus of academic texts. The main objective is to identify how "Made in Italy" is conceptualized across different academic disciplines and provide strategic insights for cultural and industrial applications.

## Features

### 🔹 Text Data Processing
- Uses **pandas** for structured data manipulation and analysis.
- Implements **regular expressions (`re` library)** for pattern extraction.
- Handles **JSON data** for structured storage and retrieval.

### 🔹 Natural Language Processing
- Employs **spaCy** and **NLTK** for tokenization, lemmatization, and linguistic analysis.
- Extracts key terms using **TF-IDF** and **TextRank**.
- Summarizes documents using the **sumy** library.

### 🔹 Semantic and Thematic Analysis
- Implements **Latent Dirichlet Allocation (LDA)** for topic modeling.
- Uses **word embeddings (Word2Vec, GloVe, and BERT)** for semantic similarity detection.
- Clusters documents using **hierarchical and k-means clustering**.

### 🔹 Visual Representations
- Generates **word clouds** for frequency analysis.
- Uses **dendrograms and heatmaps** to visualize thematic similarities.
- Analyzes **timeline trends** of academic discourse over time.

## Methodology

### 🔸 Data Acquisition & Preprocessing
1. **Corpus Selection:**
   - Academic papers, books, and reports on "Made in Italy."
2. **Text Cleaning:**
   - Removal of stopwords, punctuation, and special characters.
   - Tokenization and lemmatization.
3. **Normalization:**
   - Standardizing text formats and encoding.

### 🔸 Analysis Techniques
- **Frequency Analysis**: Identifies the most common terms and bigrams.
- **Topic Modeling (LDA)**: Extracts latent themes from the corpus.
- **Semantic Clustering**: Groups similar texts based on word embeddings.
- **Sentiment Analysis**: Assesses academic perspectives on "Made in Italy."
- **Keyword Extraction**: Identifies field-specific terminology.

## Project Structure
```
├── data/               # Raw and processed text data
├── notebooks/          # Jupyter notebooks with analysis steps
├── src/               # Python scripts for text processing
│   ├── preprocessing.py
│   ├── topic_modeling.py
│   ├── clustering.py
│   ├── visualization.py
│   ├── summarization.py
├── results/           # Outputs (word clouds, topic distributions, etc.)
├── README.md          # Project documentation
```

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/NLP-Strategy-Comprehension.git
cd NLP-Strategy-Comprehension
pip install -r requirements.txt
```

## Usage
Run the main script to process text data and perform the analysis:
```bash
python src/main.py
```
For interactive analysis, open Jupyter Notebook:
```bash
jupyter notebook
```

## Results & Insights
The study reveals the most significant themes associated with "Made in Italy," such as:
- **Craftsmanship & Quality**: Strong academic emphasis on artisanal excellence.
- **Sustainability & Innovation**: Emerging trends in eco-friendly production.
- **Cultural Heritage**: The role of historical and artistic traditions in branding.
- **Economic & Industrial Impact**: Influence on global markets and trade policies.

The findings are visualized using:
- **Word clouds** to highlight frequent terms.
- **Thematic maps** showing relationships between different research fields.
- **Time-series analysis** to track evolving discussions over time.

## Contributors
- **Danial Bazzazi** (Author, Researcher, and Developer)
- **Prof. Luigi Salmaso** (Supervisor)
- **Dr. Nicolò Biasetton & Dr. Elena Barzizza** (Co-supervisors)

## Acknowledgments
This research was conducted as part of the Master's Thesis in **Management Engineering** at the **University of Padova**, academic year **2024/2025**.



