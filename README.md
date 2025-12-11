# sgns-embedding-viz
# Wiki Word2Vec PyTorch 
A simple implementation of a Word2Vec model (Skip-Gram with Negative Sampling) built from scratch using PyTorch. This project scrapes specific medical and tech topics from Wikipedia, trains word embeddings, and visualizes relationships using Cosine Similarity and PCA.

## Features
* **Data Pipeline:** Scrapes and cleans Wikipedia articles (topics: Cancer, Deep Learning, Healthcare, etc.).
* **Custom Model:** Implements `Word2VecSGNS` (Skip-Gram Negative Sampling) in PyTorch.
* **Analysis:** Calculates **Cosine Similarity** to find nearest semantic neighbors.
* **Visualization:** Reduces dimensions using PCA to plot word relationships in 2D.

## 🛠️ Tech Stack
* **Python 3.x**
* **PyTorch** (Model training)
* **NLTK & BeautifulSoup** (Text preprocessing)
* **Wikipedia-API** (Data collection)
* **Matplotlib** (Visualization)

## 📦 Installation

```bash
pip install torch numpy matplotlib nltk wikipedia beautifulsoup4 tqdm
