# MarketEdge AI – Stock Chart Analysis Telegram Bot

An intelligent **Telegram Bot** powered by AI that provides professional technical analysis and real-time stock charts for stocks, indices, and crypto.

---

## ✨ Overview

**MarketEdge AI** is an automated n8n workflow that turns Telegram into your personal stock market analyst. Users simply message a stock name (e.g., `Tesla`, `Reliance`, `NIFTY`, `BTC`), and the bot delivers clear, professional technical analysis along with candlestick charts.

Built with **n8n + Groq AI + LangChain**.

---

## 🚀 Features

- **Real-time Technical Analysis**
- **Automatic Chart Generation** (TradingView-style candlestick charts)
- **Multi-Market Support**:
  - US Stocks (AAPL, TSLA, NVDA, etc.)
  - Indian Stocks (RELIANCE.NS, HDFCBANK.NS, etc.)
  - Major Indices (NIFTY, SENSEX, SPX)
  - Cryptocurrency (BTC, ETH, etc.)
- **Conversation Memory** – Remembers previous messages
- **Professional Response Format** with:
  - Current trend & price summary
  - Key technical levels (Support/Resistance, Moving Averages)
  - Indicators (RSI, MACD, Volume)
  - Short-term & Medium-term outlook
  - Risk warnings
- **Responsible AI** – Never gives direct Buy/Sell advice

---

## 📋 How It Works

1. User sends message to Telegram Bot
2. AI Agent (MarketEdge AI) processes the request
3. Sub-workflow generates latest stock chart
4. AI delivers structured technical analysis + chart
5. Response is sent back to the user

---

## 🛠️ Technologies Used

- **n8n** – Workflow Automation
- **Groq** – Ultra-fast AI model
- **LangChain Agent** – With memory & tool calling
- **Telegram Bot API**
- Sub-workflow for chart generation

---

## 📥 Installation & Setup

1. Download the workflow file: `stock chart analysis.json`
2. Import it into n8n (`Workflows → Import from File`)
3. Set up the required credentials:
   - **Telegram Bot Token**
   - **Groq API Key**
4. Configure the **sub-workflow** (`sub stock`) for chart generation
5. Activate the workflow
6. Start chatting with your bot!

---

## 📸 Example Usage

- `Tesla stock analysis`
- `Show Reliance chart`
- `NIFTY today`
- `Technical analysis of BTC`
- `Apple support and resistance`

---

## 🔮 Future Improvements

- Add fundamental analysis
- Portfolio tracking
- Daily market summary alerts
- Voice message support
- Multi-language support

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 🤝 Contributing

Feel free to fork, improve, or submit pull requests. Any suggestions for better prompts, new tools, or features are welcome!

---

**Made with ❤️ for traders & investors**

---

**Give this repo a ⭐ if you find it useful!**
