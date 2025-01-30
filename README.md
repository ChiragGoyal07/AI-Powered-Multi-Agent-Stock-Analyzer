# AI-Powered-Multi-Agent-Stock-Analyzer
🔍 **An intelligent multi-agent system using Llama 3.3, PhiData, and Groq API to analyze stock fundamentals and fetch real-time market news.**

---

## 🚀 **Project Overview**
This project builds an **AI-powered multi-agent system** to automate **financial stock analysis**, integrating:  
✅ **Finance Agent** → Retrieves stock prices, analyst recommendations, and company fundamentals.  
✅ **Web Search Agent** → Fetches the latest news on stocks using DuckDuckGo.  
✅ **Team Lead Agent** → Coordinates both agents for seamless execution and structured reporting.  

🔹 **Designed for AI-driven financial insights** with **real-time data retrieval and analysis.**  
🔹 **Automates stock comparison** by combining **LLMs, APIs, and autonomous agents.**  

---

## 🏗️ **Tech Stack**
| **Technology**  | **Usage**  |
|---------------|----------|
| **Llama 3.3 (70B) via Groq API** | LLM for stock analysis and reasoning  |
| **PhiData** | Agent-based AI framework  |
| **Yahoo Finance (`yfinance`)** | Real-time stock data and analyst recommendations  |
| **DuckDuckGo API** | Fetching latest stock-related news  |
| **Python & dotenv** | Core programming & environment management  |

---

## 🔧 **Installation & Setup**
1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/your-username/AI-Stock-Analyzer.git
cd AI-Stock-Analyzer
```
  
2️⃣ **Install Dependencies**  
```bash
pip install -r requirements.txt
```
  
3️⃣ **Set Up API Keys**  
Create a `.env` file and add your Groq API key:  
```plaintext
GROQ_API_KEY=your_api_key_here
```

---

## 🚀 **How It Works**
Run the multi-agent system using:  
```bash
python main.py
```
The **Team Lead Agent** will:  
✔ **Fetch stock fundamentals & recommendations** via Yahoo Finance.  
✔ **Retrieve real-time news** using DuckDuckGo.  
✔ **Present structured insights** in markdown tables.  

---

## 📊 **Example Output**
```
📈 Stock Comparison: Tesla (TSLA) vs. Microsoft (MSFT)

| Metric            | Tesla (TSLA)  | Microsoft (MSFT) |
|------------------|--------------|----------------|
| Market Cap       | $800B        | $2.5T         |
| PE Ratio        | 45.3         | 35.1          |
| Analyst Rating  | Buy          | Strong Buy    |

📰 Latest News:
- "Tesla sees record deliveries in Q4" (source: Reuters)
- "Microsoft AI investments boost cloud growth" (source: Bloomberg)
```

---

## 📌 **Why This Project?**
✅ **Practical application of AI agents** in real-world finance.  
✅ **Combines LLMs, APIs, and autonomous agents** for decision-making.  
✅ **Customizable & Scalable** for different financial datasets.  

---

## 🤝 **Contributions & Future Enhancements**
🔹 **Enhance stock trend predictions** with time-series forecasting.  
🔹 **Integrate Bloomberg or alternative financial APIs.**  
🔹 **Improve UI/visualization for financial insights.**  

---

## ⭐ **Let's Connect!**
📩 Feel free to reach out for collaboration or suggestions!  
🔗 **LinkedIn:** [Your Name](https://linkedin.com/in/yourprofile)  
🔗 **GitHub:** [@your-username](https://github.com/your-username)  

---

This **README** ensures your project looks **professional, easy to understand**, and **technically sound**, making it **resume-ready for GitHub linking!** 🚀 Let me know if you want any tweaks!
