# 👋 Hi there, I'm Nguyen Le Anh Tu

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Anhtu12022004-181717?style=for-the-badge&logo=github)](https://github.com/Anhtu12022004)
[![Email](https://img.shields.io/badge/Email-nguyenleanhtu13579%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nguyenleanhtu13579@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nguyenleanhtu22120399-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nguyenleanhtu22120399)
[![Location](https://img.shields.io/badge/Location-Ho%20Chi%20Minh%20City%2C%20Vietnam-00B4D8?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 🧠 About Me

I am a final-year **Computer Science** student at the **University of Science — VNUHCM** (GPA: 3.7/4.0), passionate about researching and applying **Deep Learning** to real-world problems in **Computer Vision** and **Natural Language Processing**.

I enjoy building AI systems end-to-end. My goal is to become a **Machine Learning Engineer** who contributes to innovative, scalable AI solutions.

---

## 🚀 Featured Projects

### 📰 [News Aggregator Multi-Agent System](https://github.com/Anhtu12022004/News-Aggregator-Agent)

> An automated news aggregator powered by a collaborative **Multi-Agent architecture** and **OpenAI GPT-4o-mini**, featuring a real-time Glassmorphism Web UI.

**Highlights:**
- Designed a **4-agent collaborative pipeline**: Fetcher Agent (RSS crawling) → Analyst Agent (quality scoring via Structured Outputs) → Summary Agent (concise 3–4 sentence summaries) → Compiler Agent (Markdown report generation)
- Implemented **OpenAI Structured Outputs** in the Analyst Agent for rubric-based quality scoring (0–10), automatically filtering out low-quality articles
- Built a **real-time Web UI** with Dark Mode Glassmorphism design and **NDJSON Generator Streaming** for live per-agent progress logs
- Architected a **centralized `config.py`** for zero-code tuning of categories, score thresholds, model selection, and summary length
- Integrated **timezone-aware date filtering** to process only same-day articles, minimizing token cost and ensuring news freshness

**Tech stack:** `Python` `OpenAI API (GPT-4o-mini)` `Flask` `BeautifulSoup` `JavaScript` `HTML/CSS`

---

### 📚 [Semantic Book Recommender](https://github.com/Anhtu12022004/Semantic-Book-Recommender)

> An AI-powered book recommendation app supporting **natural language search**, built on real-world data crawled from Fahasa.com.

**Highlights:**
- Crawled and preprocessed a real-world Vietnamese book dataset from **Fahasa.com** using Selenium/BeautifulSoup
- Fine-tuned **XLM-RoBERTa** (multilingual transformer) for genre classification into top-3 categories
- Integrated **OpenAI text-embedding-3-small** + **ChromaDB** for semantic vector search (top-100 similarity retrieval)
- Deployed an interactive **Gradio UI** with price filtering, gallery view, and book detail pages
- Explored practical **Retrieval-Augmented Generation (RAG)** concepts through contextual retrieval and vector search

**Tech stack:** `Python` `HuggingFace` `OpenAI API` `ChromaDB` `LangChain` `Gradio`

---

### 📄 [Scientific Paper Classification](https://github.com/Anhtu12022004/Scientific-Paper-Classification)

> An end-to-end **multi-label NLP pipeline** for automatic categorization of academic papers.

**Highlights:**
- Collected and processed ~**314,000 papers** from the ArXiv API for multi-label classification
- Built baseline models using **TF-IDF** with Logistic Regression, Linear SVC, and KNN for comparative evaluation
- Fine-tuned **SciBERT** with TensorFlow, achieving **Macro F1 = 0.77** — outperforming all traditional ML baselines
- Conducted a comprehensive comparative analysis of model architectures, evaluation metrics, and NLP pipeline performance

**Tech stack:** `Python` `TensorFlow` `HuggingFace (SciBERT)` `Scikit-learn` `Jupyter Notebook`

---

### 🤚 [Fingerprint Recognition System](https://github.com/Anhtu12022004/Fingerprint-Recognition-System)

> A biometric fingerprint verification system built on a **Siamese Neural Network**.

**Highlights:**
- Designed and trained a **Siamese Network** on positive/negative image pairs for similarity learning
- Focused on image preprocessing and manual feature extraction for robust biometric recognition
- Built a complete pipeline: data preparation → model training → evaluation

**Tech stack:** `TensorFlow/Keras` `Python` `Jupyter Notebook`

---

### 🔬 [CUDA Autoencoder — CIFAR-10 Image Reconstruction](https://github.com/Anhtu12022004/Autoencoder-Project---CIFAR-10-Image-Reconstruction)

> A complete Autoencoder built entirely from scratch in **C++/CUDA**, with no ML library dependencies.

**Highlights:**
- Developed across **4 progressive optimization phases**: CPU Baseline → GPU Basic → GPU Optimized → SVM Integration
- Achieved **~17× speedup** over the CPU baseline
- Applied advanced CUDA techniques: **Kernel Fusion** (Conv2D + ReLU + MaxPool), **Loop Unrolling**, **CUDA Streams** (×4) with Quad Buffering, and **Pinned Memory** — reducing memory bandwidth by ~50%
- Integrated the trained Encoder (8,192-dim features) as a feature extractor for an **SVM classifier**, reaching ~63% accuracy on CIFAR-10

**Tech stack:** `C++` `CUDA` `Python` `Scikit-learn` `Jupyter Notebook`

---


## 🛠️ Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Frameworks & Libraries
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

### AI / ML Domains
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-FF6F61?style=for-the-badge)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-0078D4?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-8A2BE2?style=for-the-badge)
![LLM Applications](https://img.shields.io/badge/LLM%20Applications-FF9900?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-20B2AA?style=for-the-badge)
![Embeddings & Vector Search](https://img.shields.io/badge/Embeddings%20%26%20Vector%20Search-6A0DAD?style=for-the-badge)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-E63946?style=for-the-badge)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge)
![Conda](https://img.shields.io/badge/Conda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

</div>

---

## 🎓 Education & Certificates

**🏫 University of Science — VNUHCM**
`2022 – 2026` | Computer Science | **GPA: 3.7 / 4.0**

**📜 Certificates:**
- 🏅 [Machine Learning — DeepLearning.AI](https://www.coursera.org/account/accomplishments) *(Coursera, 2025)*
- 🏅 [Google Data Analytics](https://www.coursera.org/account/accomplishments) *(Coursera, 2025)*


---

## 💡 What I'm Interested In

- 🔭 Researching and applying **Transformer architectures** across CV & NLP tasks
- 🌱 Exploring **LLM orchestration**, **Agentic AI systems**, and **RAG pipelines**
- 🤝 Building end-to-end AI applications — from data collection to production deployment

---

<div align="center">

*"Build things from scratch to truly understand them."*

📩 Contact: **nguyenleanhtu13579@gmail.com** | 📍 Ho Chi Minh City, Vietnam

</div>
