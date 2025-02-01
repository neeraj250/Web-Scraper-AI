# Web Scraper AI

This project is designed to scrape websites and retrieve relevant information based on user prompts. It integrates **Streamlit** for the frontend, **Selenium** for web scraping, and **LangChain** for leveraging large language models (LLMs) to parse and process the data. Additionally, **Bright Data** is used to handle websites with CAPTCHA and other anti-bot mechanisms.

## 🚀 Features
- **Web Scraping:** Extract data from websites efficiently using Selenium.
- **LLM Integration:** Utilize LangChain to interact with LLMs for data parsing and analysis.
- **Proxies & CAPTCHA Handling:** Use Bright Data to bypass CAPTCHA and other anti-scraping protections.
- **User-Friendly Interface:** Built with Streamlit for a simple and intuitive frontend experience.

---

## 🛠️ Prerequisites
- **Python 3.x** installed on your machine.
- **Google Chrome Browser** (for Selenium compatibility).
- **Ollama** installed (for LLM model management).
- **Bright Data Account** for handling CAPTCHA and proxy management.

---

## ⚙️ Installation Guide

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/neeraj-badam/Web-Scraper-AI.git
   cd Web-Scraper-AI
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Install Google Chrome:**
   - Download Chrome based on compatibility with your system from [Chrome for Testing](https://googlechromelabs.github.io/chrome-for-testing/#stable).

5. **Set Up Ollama:**
   - Visit [Ollama GitHub Repository](https://github.com/ollama/ollama) to download and install Ollama.
   - Install the required LLM model using the following command:
     ```bash
     ollama pull <model-name>
     ```
     *Note:* Larger models offer better performance and accuracy.

6. **Configure Bright Data:**
   - Create an account at [Bright Data](https://brightdata.com/).
   - Set up proxies for scraping and enable the **'CAPTCHA Solver'** under configurations.
   - Integrate Bright Data proxy credentials into the project configuration for seamless scraping.

---

## 🚀 Running the Application

After completing the setup, run the application using Streamlit:

```bash
streamlit run main.py
```

This will launch the web interface in your default browser.

---

## 📄 Additional Notes
- Ensure **ChromeDriver** is compatible with your installed version of Chrome.
- Adjust any necessary **Selenium settings** in the `main.py` file if required.
- Keep the virtual environment activated while running the project.
- For websites with advanced bot protections, ensure Bright Data's proxies and CAPTCHA solver are properly configured.

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## 📧 Contact
For any queries or issues, please reach out via [GitHub Issues](https://github.com/neeraj-badam/Web-Scraper-AI/issues).

---

**Happy Scraping! 🚀**
