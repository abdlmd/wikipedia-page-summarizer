# 📘 Wikipedia Page Summarizer

A simple AI project that scrapes content from **Wikipedia** using `BeautifulSoup` and generates a concise summary with **Google Gemini AI**.  
Just provide a Wikipedia URL, and the notebook fetches the article’s content, cleans it, and returns an easy-to-read summary with key points.

---

## 🚀 Features
- Scrapes Wikipedia articles using `requests` + `BeautifulSoup`
- Cleans the content for better readability
- Uses **Google Gemini AI** (`gemini-2.5-flash`) to generate summaries
- Runs directly inside a **Jupyter Notebook**
- Keeps your API key secure with `.env`

---

## 🛠️ Setup Instructions

1. **Clone the repository**  
   $ git clone https://github.com/abdlmd/wikipedia-page-summarizer.git  
   $ cd wikipedia-page-summarizer

2. **Create a virtual environment (recommended)**  
   $ python -m venv venv  
   # Activate it:  
   $ source venv/bin/activate   # On Mac/Linux  
   $ venv\Scripts\activate      # On Windows

3. **Install dependencies**  
   $ pip install -r requirements.txt

4. **Set up your `.env` file**  
   Create a file named `.env` in the project root and add your Gemini API key:  
   GEMINI_API_KEY=your_api_key_here

5. **Run the Jupyter Notebook**  
   $ jupyter notebook wikipedia-page-summarizer.ipynb
