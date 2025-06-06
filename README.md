# Advance-AI-Scraper

# 🚀 Advance AI Scraper

[Live Demo 🔗](https://advance-ollama-scraper.streamlit.app/)

Advance AI Scraper is a cutting-edge, intelligent web scraping application built using **Python** and **Selenium WebDriver**, designed to extract rich, dynamic content from all kinds of websites — including JavaScript-heavy, dynamically rendered pages. What makes this tool revolutionary is its seamless integration with Large Language Models (LLMs), supporting both **Ollama 3.2** and **DeepSeek R1**. By combining traditional scraping with AI-powered content parsing, this project enables a more accurate and context-aware way of extracting meaningful information from raw HTML and DOM structures.

The scraper intelligently utilizes **BrightData** proxies to rotate IPs, avoid rate limiting, and bypass bot detection, ensuring reliability even on highly secured or geo-blocked websites. Whether you're scraping e-commerce listings, articles, structured data, or complex nested content, Advance AI Scraper handles it with speed and precision.

The embedded LLM models (Ollama 3.2 or DeepSeek R1) are used to **parse and extract only the necessary data**, removing noise and extra content automatically. This makes the scraper ideal for building datasets, training machine learning models, and creating data-rich applications without having to write dozens of regexes or XPath queries manually.

---

### ✨ Features

- 🌐 Scrape **any type of website** (static or dynamic)
- 🤖 Uses **Ollama 3.2** or **DeepSeek R1** for intelligent data parsing
- 🧠 Context-aware information extraction using LLMs
- 🛡️ Proxy support via [BrightData](https://brightdata.com/)
- ⚙️ Built with **Selenium WebDriver**
- 🧩 Works out-of-the-box with **Streamlit UI**

---

### 🚀 Try it Live

👉 [Click here to open the app](https://advance-ollama-scraper.streamlit.app/)

---

### 🛠️ Tech Stack

- Python
- Streamlit
- Selenium WebDriver
- LangChain
- Ollama 3.2 / DeepSeek R1 (LLMs)
- BrightData Proxies

---

### 📦 Installation

```bash
git clone https://github.com/Dhruvgoyalll/Advance-AI-Scraper.git
cd Advance-AI-Scraper
pip install -r requirements.txt
streamlit run main.py
