# 🔍 Semantic Research Paper Search Engine

A semantic search engine for research papers built using **Sentence Transformers** and **FAISS**. Unlike traditional keyword-based search, this project understands the meaning of a user's query and retrieves the most relevant research papers based on semantic similarity.

## 📌 Project Overview

This project uses a pretrained transformer model to convert research paper abstracts into dense vector embeddings. These embeddings are indexed using FAISS, enabling fast and efficient similarity search over thousands of research papers.

The system allows users to search for research papers using natural language queries, making it easier to discover relevant literature even when exact keywords are not present.

---

## 🚀 Features

* Semantic search using natural language queries
* Fast similarity search powered by FAISS
* High-quality sentence embeddings using Sentence Transformers
* Data preprocessing and exploratory data analysis (EDA)
* Efficient embedding storage and loading
* Scalable architecture for large research paper datasets

---

## 🛠️ Tech Stack

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Sentence Transformers
* FAISS
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📂 Project Structure

```
├── EDA.ipynb              # Data preprocessing and embedding generation
├── Search_Engine.ipynb    # Semantic search implementation using FAISS
├── dataset.md             # Dataset information
```

---

## 📊 Dataset

This project uses the **ML-ArXiv-Papers** dataset available on Hugging Face.

The dataset contains research papers with information such as:

* Title
* Abstract
* Categories
* Authors

Dataset information is provided in `dataset.md`.

---

## ⚙️ How It Works

1. Load the research paper dataset.
2. Clean and preprocess the data.
3. Generate sentence embeddings using the pretrained `all-MiniLM-L6-v2` model.
4. Store embeddings for efficient reuse.
5. Build a FAISS index from the embeddings.
6. Accept a natural language query from the user.
7. Retrieve the most semantically similar research papers.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/semantic-search-engine.git
cd semantic-search-engine
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open `EDA.ipynb`.
2. Run all cells to preprocess the dataset and generate embeddings.
3. Open `Search_Engine.ipynb`.
4. Run the notebook.
5. Enter a search query to retrieve the most relevant research papers.

---

## 📈 Future Improvements

* Web interface using Streamlit or Flask
* PDF viewer integration
* Hybrid keyword + semantic search
* Query autocomplete
* Research paper recommendation system
* Support for multiple datasets
* Docker deployment

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience with:

* Natural Language Processing (NLP)
* Semantic Search
* Vector Embeddings
* Transformer Models
* FAISS Indexing
* Research Paper Retrieval Systems
* Data Preprocessing
* Exploratory Data Analysis (EDA)

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.
