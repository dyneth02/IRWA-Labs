# Information Retrieval & Web Analytics (IRWA) Framework

This repository focuses on the technical backbone of modern search engines and text processing systems. It documents the journey from basic text manipulation to building complex data structures like Positional Indexes and implementing Boolean logic for document retrieval.

## 🎯 Core Objectives
- Understanding how search engines index vast amounts of unstructured text.
- Implementing NLP preprocessing pipelines (Normalization, Tokenization, Stop-word removal).
- Developing algorithms for efficient data retrieval and similarity measurement.

## 📂 Project Roadmap

### 🔍 1. Search Engine Indexing (The Core)
* **Inverted Indexing:** Implementation of the standard "term-to-document" mapping. Includes logic to handle folder-based corpora where documents are parsed and mapped to a searchable dictionary.
* **Positional Indexing:** Advanced indexing that stores the exact position of words. This enables **Phrase Searching** (e.g., finding the exact sequence "Machine Learning") rather than just individual keywords.
* **Boolean Retrieval:** Custom functions to perform `AND`, `OR`, and `NOT` operations on indexed terms to filter document results.

### ✂️ 2. NLP & Text Preprocessing
* **Preprocessing Pipelines:** Systematic removal of punctuation using `str.maketrans`, lowercasing, and whitespace handling.
* **Tokenization & N-grams:** breaking down sentences into unigrams, bigrams, and trigrams to analyze word frequency and context.
* **Feature Extraction:** Using `CountVectorizer` to transform text into numerical vectors for machine learning compatibility.

### 📐 3. Mathematical Foundations
* **Cosine Similarity:** Visualizing and calculating the cosine function—the mathematical foundation for measuring the similarity between two text documents in a vector space.
* **Statistical Analysis:** Methods to count character types (Upper, Lower, Digits, Special) and analyze series summation.

## 🛠 Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `NLTK`: For tokenization and N-grams.
    - `Scikit-Learn`: For vectorization and document-term matrices.
    - `NumPy & Pandas`: For data structure management.
    - `Matplotlib`: For mathematical function visualization.

## 🧪 Detailed Lab Breakdown
* **IRWA_Lab001:** Python fundamentals, list manipulation, and basic string statistics.
* **IRWA_Lab02 & Part A:** Deep dive into text normalization, punctuation removal efficiency, and NLTK tokenization.
* **IRWA_Lab03 & Lab04:** Architecture for building inverted indexes from scratch and handling file-system corpora.
* **IRWA_Lab05:** Implementation of the **Positional Index** and testing Boolean retrieval logic (AND/NOT queries).

## 🚀 Usage
To explore the indexing logic:
1. Clone the repository.
2. Navigate to `IRWA_Lab05.ipynb` to see the most advanced implementation of the Positional Index.
3. Use the provided `Teaching Guides` for a step-by-step walkthrough of the indexing logic.
