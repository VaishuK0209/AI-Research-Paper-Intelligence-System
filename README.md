<div align="center">

# 🔍 Semantic Research Paper Search Engine

### AI-powered Semantic Search for Research Papers using Sentence Transformers & FAISS

<p>
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/NLP-Semantic%20Search-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FAISS-Vector%20Search-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-red?style=for-the-badge" />
</p>

*A semantic search engine that understands the **meaning** of your query—not just the keywords.*

</div>

---

## 📖 About the Project

Finding relevant research papers through traditional keyword search can be challenging because different papers often describe the same concept using different terminology.

This project solves that problem by implementing a **Semantic Research Paper Search Engine** powered by **Natural Language Processing (NLP)** and **Transformer-based sentence embeddings**.

Instead of matching exact words, the system understands the **context and semantic meaning** of a user's query, allowing it to retrieve the most relevant research papers—even when the query and the paper use different vocabulary.

The project was developed as part of the **CBSOT Summer Internship 2026** to explore modern Information Retrieval techniques using state-of-the-art NLP models.

---

# ✨ Key Features

* 🔍 Context-aware semantic search
* 🤖 Transformer-based text embeddings
* ⚡ Ultra-fast similarity search with FAISS
* 📚 Research paper retrieval using Natural Language queries
* 📊 Data preprocessing and exploratory data analysis
* 💾 Efficient embedding storage for faster searches
* 📈 Scalable architecture for large document collections
* 🧠 Uses pretrained Sentence Transformer models

---

# 🛠️ Tech Stack

| Category             | Technologies                 |
| -------------------- | ---------------------------- |
| Programming Language | Python                       |
| NLP                  | Sentence Transformers        |
| Vector Search        | FAISS                        |
| Data Processing      | Pandas, NumPy                |
| Machine Learning     | Scikit-learn                 |
| Visualization        | Matplotlib, Seaborn          |
| Environment          | Jupyter Notebook             |
| Dataset              | Hugging Face ML-ArXiv Papers |

---

# 📂 Project Structure

```text
Semantic-Research-Paper-Search/
│
├── EDA.ipynb
├── Search_Engine.ipynb
├── dataset.md
├── requirements.txt
├── .gitignore
└── README.md
```

---

# ⚙️ Workflow

```text
Research Paper Dataset
          │
          ▼
Data Cleaning & Preprocessing
          │
          ▼
Sentence Transformer
(all-MiniLM-L6-v2)
          │
          ▼
Generate Vector Embeddings
          │
          ▼
Store Embeddings
          │
          ▼
Build FAISS Index
          │
          ▼
User Natural Language Query
          │
          ▼
Convert Query to Embedding
          │
          ▼
Similarity Search
          │
          ▼
Top Relevant Research Papers
```

---

# 📊 Dataset

This project uses the **ML-ArXiv-Papers** dataset available on **Hugging Face**.

The dataset contains thousands of Machine Learning research papers, including:

* Research Paper Title
* Abstract
* Authors
* Categories

The complete dataset reference is available in **dataset.md**.

---

# 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/semantic-research-paper-search.git
cd semantic-research-paper-search
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

### Step 1 — Generate Embeddings

Run

```text
EDA.ipynb
```

This notebook:

* Loads the dataset
* Cleans the data
* Performs Exploratory Data Analysis
* Generates semantic embeddings

---

### Step 2 — Search Papers

Run

```text
Search_Engine.ipynb
```

This notebook:

* Loads saved embeddings
* Creates (or loads) the FAISS index
* Accepts a natural language query
* Returns the most semantically similar research papers

---

# 💡 Example

### User Query

```text
Deep learning techniques for image classification
```

### Output

✔ Most Relevant Research Papers

✔ Similarity Scores

✔ Paper Titles

✔ Research Abstracts

---

# 🧠 How Semantic Search Works

Unlike traditional keyword search:

❌ Keyword Search

* Matches exact words
* Misses related concepts
* Sensitive to wording

✅ Semantic Search

* Understands context
* Finds conceptually similar papers
* Uses dense vector embeddings
* Produces more meaningful search results

---

# 📚 What I Learned

Through this project I gained practical experience with:

* Natural Language Processing (NLP)
* Semantic Search
* Transformer Models
* Sentence Embeddings
* Vector Databases
* FAISS Indexing
* Information Retrieval
* Research Paper Retrieval Systems
* Data Preprocessing
* Exploratory Data Analysis

---

# 🎯 Future Enhancements

* 🌐 Streamlit Web Application
* 📄 PDF Upload & Search
* 🤖 Research Paper Recommendation System
* 🔍 Hybrid Keyword + Semantic Search
* 📊 Interactive Search Dashboard
* 🐳 Docker Support
* ☁ Cloud Deployment
* 🔌 REST API Integration

---

# 🤝 Contributing

Contributions are always welcome!

If you have ideas to improve this project, feel free to:

* Fork the repository
* Create a new branch
* Submit a Pull Request

---

# ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub.

It helps support the project and motivates future improvements.

---

# 👨‍💻 Author

**Vaishnavi Kushwah**

Developed during the **CBSOT Summer Internship 2026**.

Let's connect and collaborate on **AI**, **Machine Learning**, **NLP**, and **Open Source** projects!

