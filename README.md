# 🔎 Custom Semantic Search Engine using Exa API

A simple Python-based custom search engine that uses the [Exa API](https://exa.ai) to perform **semantic web searches** using Large Language Models (LLMs). Unlike traditional keyword-based search, this engine understands the **context** of your query for more relevant results.

## 🚀 Features
- Semantic search using Exa's LLM-powered API
- Clean CLI output: only titles and URLs
- Filter by number of results and domain (e.g., TikTok, GitHub, Twitter)
- Easily customizable for personal or research use

## 🧰 Requirements
- Python 3.10+
- [Exa API Key](https://exa.ai) (Free with 1000 monthly requests)

## 🛠️ Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/custom-search-engine-exa.git
   cd custom-search-engine-exa
2.Install the Exa Python SDK:
```bash
pip install exa_py
```
3.Add your API key:
Open main.py and replace 'YOUR_KEY_HERE' with your actual key:
```bash
exa = Exa('your-api-key')
```
4.Run the app:
```bash
python3 main.py
```


Search here: best Python tutorials
Title: 10 Best Python Tutorials for Beginners
URL: https://example.com/python-tutorials

Title: Learn Python – Full Course for Beginners
URL: https://example.com/learn-python


🔧 Customization Tips
Change num_results to show more or fewer search results.

Use include_domains=['https://www.tiktok.com'] to limit results to specific sites.

Use category='tweet' or category='papers' for domain-specific filtering.

Made with ❤️ using Exa.ai

![image](https://github.com/user-attachments/assets/c4cd7c59-2a91-4a01-8472-a5fc18c72a0e)
