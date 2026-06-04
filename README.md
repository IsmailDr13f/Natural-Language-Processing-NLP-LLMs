<div align="center">
  <h1>Natural Language Processing (NLP) & LLMs</h1>
  <p>
    <a href="#"><img src="https://img.shields.io/badge/Python-3.8+-blue.svg?logo=python&logoColor=white" alt="Python"></a>
    <a href="#"><img src="https://img.shields.io/badge/Scikit--Learn-Machine_Learning-orange.svg?logo=scikit-learn&logoColor=white" alt="Scikit-Learn"></a>
    <a href="#"><img src="https://img.shields.io/badge/Hugging%20Face-Transformers-yellow.svg?logo=huggingface&logoColor=white" alt="Hugging Face"></a>
    <a href="#"><img src="https://img.shields.io/badge/LangChain-LLMs-green.svg" alt="LangChain"></a>
    <a href="#"><img src="https://img.shields.io/badge/License-MIT-success.svg" alt="License: MIT"></a>
  </p>
  <p><em>Your ultimate playground for mastering Natural Language Processing, from basic Regex rules to state-of-the-art Large Language Models.</em></p>
</div>

---

### Table of Contents
**[Goal of the Repository](#goal-of-the-repository)** | **[What You'll Find & Benefit From](#what-youll-find--benefit-from)** | **[Tools & Technologies Used](#tools--technologies-used)** | **[How to Run Locally](#how-to-run-locally)**

---

## Goal of the Repository

Welcome to the **Natural Language Processing & LLMs** repository. This space was built with a clear mission: to demystify the world of NLP and provide a hands-on, practical journey from traditional text processing techniques to modern, cutting-edge Large Language Models (LLMs). 

Whether you are just starting out or looking to sharpen your AI engineering skills, this repository serves as a comprehensive guide. We will explore everything from basic rule-based text extraction to building fully-fledged Retrieval-Augmented Generation (RAG) applications that can converse with your documents.

## What You'll Find & Benefit From

This repository is structured into focused projects, each tackling a unique aspect of NLP:

- **Rule-Based NLP & Word Embeddings (Arabic Language Focus):** Master foundational concepts like Regex and early text representations, diving into the complexities of Arabic text processing.
- **Language Modeling with Scikit-Learn:** Learn how traditional machine learning algorithms handle text classification and predictive modeling.
- **Transformers (Regression, Classification & Text Generation):** Step into the modern era of NLP by leveraging the power of Transformer architectures for complex tasks.
- **End-to-End Scraping & NLP Pipelines:** See how data is collected from the wild via web scraping and fed directly into powerful Arabic text analysis pipelines.
- **Talk With Your Documents (RAG):** Experience the capabilities of Large Language Models by building a system that ingests university data (or any documents) and allows you to chat with them intelligently.

**By exploring this repo, you will:**
- Grasp the evolution of NLP techniques.
- Gain practical experience building real-world AI applications.
- Learn how to handle challenging tasks like Arabic NLP.
- Walk away with portfolio-ready projects.

## Tools & Technologies Used

To make this journey possible, we rely on a fantastic stack of modern data science and AI tools:

- **Programming Language:** Python
- **Machine Learning & Data Processing:** Scikit-Learn, Pandas, NumPy
- **Deep Learning & NLP Libraries:** Hugging Face `transformers`, NLTK, spaCy
- **LLM Frameworks:** LangChain (for RAG and document chatting)
- **Data Scraping:** BeautifulSoup, Selenium, Scrapy
- **Environment Management:** Jupyter Notebooks and standard Python scripts

## How to Run Locally

Want to dive in and experiment on your own machine? Just follow these steps:

**1. Clone the repository:**
Open your terminal and grab a copy of this code:
```bash
git clone https://github.com/IsmailDr13f/Natural-Language-Processing-NLP-LLMs.git
cd Natural-Language-Processing-NLP-LLMs
```

**2. Set up your environment:**
It is always best to use a virtual environment to keep your packages isolated.
```bash
# Create a virtual environment named 'nlp-env'
python -m venv nlp-env

# Activate it (Windows)
nlp-env\Scripts\activate

# Activate it (Mac/Linux)
source nlp-env/bin/activate
```

**3. Install the dependencies:**
Navigate to whichever specific project folder you would like to explore, and install the required packages. You can use the root requirements file:
```bash
pip install -r requirements.txt
```
*(Note: Some sub-projects might have their own specific dependencies, so be sure to check inside their respective folders)*

**4. Start exploring:**
Fire up Jupyter Notebook or run the Python scripts directly to see the code in action:
```bash
jupyter notebook
```

Happy coding, and enjoy the journey through the fascinating world of NLP.