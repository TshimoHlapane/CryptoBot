# 💬 CryptoBuddy – A Smart Crypto Chatbot

CryptoBuddy is a simple, beginner-friendly chatbot built using Python in Google Colab. It helps users explore basic cryptocurrency insights like price trends, sustainability scores, and real-time pricing—while reminding them to do their own research!

## 🚀 Features

- 📈 Answers questions like:
  - "Which crypto is trending up?"
  - "What's the most sustainable coin?"
  - "What is the price of ETH?"
- 🌱 Recommends coins based on sustainability and profitability
- 💡 Converts aliases like `BTC` to `Bitcoin`, `ETH` to `Ethereum`, etc.
- 🔌 Pulls real-time prices using the [CoinGecko API](https://www.coingecko.com/en/api)
- ⚠️ Includes an ethics disclaimer to promote responsible investing
- 💬 Interactive chat interface using ipywidgets

## 🛠️ Tech Stack

- Python
- ipywidgets (for interactive inputs in Google Colab)
- Requests (for real-time data via CoinGecko API)

## 📦 Installation

1. Open in [Google Colab](https://colab.research.google.com/)
2. Install dependencies:

```python
!pip install ipywidgets requests
```

## 🎮 Usage

1. Run the notebook in Google Colab
2. Type your question in the text input box
3. Press Enter to get your response

Example questions:
- "What's the price of Bitcoin?"
- "Which crypto is most sustainable?"
- "What's trending in crypto?"
- "What's the best investment right now?"

## ⚠️ Disclaimer

This chatbot is for educational purposes only. Always do your own research before making any investment decisions. Cryptocurrency investments are inherently risky and volatile.

## 🔄 Updates

The bot currently supports:
- Bitcoin (BTC)
- Ethereum (ETH)
- Cardano (ADA)

More cryptocurrencies can be added by extending the `crypto_db` and `coin_aliases` dictionaries in the code.
