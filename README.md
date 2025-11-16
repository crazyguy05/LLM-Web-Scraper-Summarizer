#  AI-Powered Website Summarizer (Groq LLaMA-3)

This is a practice AI engineering project where I built a Webpage Summarizer using Python, web scraping, and the Groq LLaMA-3 model.
It extracts readable content from any website and generates a clean, markdown-formatted summary using an LLM.

This project helped me learn the fundamentals of:

* LLM integration
* Prompt engineering
* Web scraping
* API workflows
* Environment variables
* Notebook-based experimentation

---

##  Features

* Scrapes any webpage and extracts text content
* Cleans and processes HTML into readable text
* Sends content to Groq’s LLaMA-3 model for summarization
* Uses system + user prompts for structured output
* Outputs neat, easy-to-read markdown summaries
* Fully implemented in a Jupyter Notebook (for practice & learning)

---

##  Tech Stack

* **Python**
* **Groq API** (LLaMA-3 models)
* **Requests** (web download)
* **BeautifulSoup4** (HTML parsing)
* **python-dotenv** (API key handling)
* **Jupyter Notebook**

---

##  Installation & Setup

### 1️. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME
cd YOUR_REPO_NAME
```

### 2️. Install dependencies

```bash
pip install -r requirements.txt
```

### 3️. Add your API key

Create a `.env` file in the project root:

```
GROQ_API_KEY=your_groq_key_here
```

Make sure `.env` is protected by `.gitignore`.

### 4️. Open the notebook

Run the Jupyter Notebook:

```
summarizer.ipynb
```

Execute the cells from top to bottom.

---

##  Project Structure

```
webpage-summarizer/
│
├── summarizer.ipynb       # Main Jupyter Notebook implementation
├── scraper.py             # Helper: extracts text from webpage
├── README.md
├── .gitignore
└── (no .env in repo)
```

---

##  What I Learned

* How LLMs process system/user messages
* How to integrate Groq’s API into Python
* How to handle environment variables securely
* How to structure a prompt for summarization
* How to extract meaningful content from messy HTML
* How to build simple AI pipelines end-to-end

---

##  Sample Output

A typical summary looks like:

```
• Main topic of the website  
• Important sections summarized  
• Key announcements or updates  
• Information extracted in clean markdown  
```

---

##  Future Improvements

I plan to extend this project with:

* Streamlit/Gradio Web UI
* Multi-page or multi-section summaries
* Better scraping (handle dynamic sites)
* Chunking + long-context support
* CLI tool (`python main.py`)

---
