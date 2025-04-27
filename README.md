# Panne-Picks 📚✨  
*An AI-Powered Semantic Book Recommender*

---

## 📚 Overview

**Panne-Picks** is an intelligent, emotion-driven book recommendation system.  
It uses advanced Natural Language Processing (NLP) and Machine Learning (ML) techniques, including **Large Language Models (LLMs)** and **Vector Search**, to help users find books matching their emotions, preferences, and interests.

This project was developed while completing the freeCodeCamp course,  
**"Build a Semantic Book Recommender with LLMs – Full Course."**

---

## 🚀 Features
- Curated **Database of Books** from Kaggle
- **Semantic Search** using vector embeddings
- **Emotion-Based Sentiment Analysis** (7+ emotion categories)
- **LLM-Powered Book Search**
- **Text Data Cleaning** (shortening descriptions, removing noise)
- **Zero-Shot Text Classification** (Fiction vs Non-Fiction)
- **Interactive Gradio Dashboard** for easy exploration
- **LLM fine-tuning and Hugging Face integration**

---

## 🧙‍♂️ Project Structure

| File | Description |
| :--- | :--- |
| `data-exploration.ipynb` | Data cleaning, removing empty spaces, shortening book descriptions |
| `vector-search.ipynb` | Creating vector embeddings and building a vector database for semantic search |
| `text-classification.ipynb` | Zero-shot text classification to tag books as Fiction or Non-Fiction |
| `sentiment-analysis.ipynb` | Extracting emotional tone (joy, sadness, suspense, etc.) using LLMs |
| `gradio-dashboard.py` | Full Gradio web app to browse and recommend books |

---

## 🛠️ Tech Stack

- **Programming Language:** Python 3.11
- **Libraries & Frameworks:**
  - `seaborn`
  - `matplotlib`
  - `pandas`
  - `kaggle`
  - `python-dotenv`
  - `langchain-community`
  - `langchain-opencv`
  - `langchain-chroma`
  - `transformers`
  - `huggingface`
  - `gradio`
  - `notebook`
  - `ipywidgets`
- **Tools Used:**
  - **Jupyter Notebook** for development
  - **Gradio** for dashboard
  - **Hugging Face** for LLMs
  - **Kaggle** for datasets

---

## 📂 Data Source

- Book data is sourced from **Kaggle**.  
- Detailed instructions for downloading the datasets are provided inside the repository.

---

## 📥 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nishantsingh604/panne-picks.git
   cd panne-picks
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in your root directory and add your OpenAI API key:

   ```bash
   OPENAI_API_KEY=your-openai-api-key-here
   ```

4. Launch Jupyter Notebook or run the Gradio dashboard:

   ```bash
   jupyter notebook
   ```

   OR

   ```bash
   python gradio-dashboard.py
   ```

---

## 🧐 How it Works

- **Data Cleaning:** Remove unwanted entries and clean book descriptions.
- **Vector Search:** Use semantic search to match user queries with similar book descriptions.
- **Text Classification:** Predict whether a book is Fiction or Non-Fiction without labeled training data.
- **Emotion Analysis:** Assign emotional scores (joy, sadness, fear, suspense, etc.) to each book.
- **User Dashboard:** An interactive UI where users can input moods or search preferences to receive book recommendations.

---

## 🤝 Credits

- **Course:** [freeCodeCamp - Build a Semantic Book Recommender with LLMs](https://www.freecodecamp.org/)
- **Instructor:** [Patrick Loeber (@patrickloeber)](https://github.com/patrickloeber)
- Thanks to the open-source community and Hugging Face for providing amazing LLM models!

---


