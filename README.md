# 🤖 AI Trading Bot (Single File Trading Terminal)

A **browser-based AI crypto trading bot and trading terminal** built entirely in a **single HTML file**.

The application simulates a professional trading dashboard with indicators, strategy engine, automated trading logic, backtesting, and risk management — all running directly in the browser without any backend server.

---

# 🚀 Features

### 📊 Trading Dashboard
- Live price simulation
- Trading chart
- EMA indicators
- Fibonacci retracement visualization
- Market indicator panel

### 🤖 Automated Trading
- Auto strategy scanning
- Trade execution simulation
- Position management
- Profit & loss tracking

### 🧠 Strategy Engine
The bot evaluates **6 market conditions** before executing trades.

Conditions used:

- EMA200 trend filter
- EMA50 trend confirmation
- Fibonacci retracement zone
- RSI momentum
- MACD histogram shift
- Volume confirmation

### 📈 Setup Grading System

| Conditions Met | Grade |
|----------------|------|
| 6 / 6 | A+ |
| 5 / 6 | A |
| 4 / 6 | B |
| <4 | WAIT |

The bot trades only when **Grade ≥ A**.

---

# 🔬 Backtesting System

The built-in backtester simulates historical trading performance and calculates:

- Total return
- Winrate
- Profit factor
- Maximum drawdown
- Sharpe ratio
- Equity curve

---

# 🛡 Risk Management

Includes basic trading protections:

- Risk-based position sizing
- Stop-loss and take-profit
- Leverage control
- Maximum daily loss settings

---

# 🏗 Project Structure

This project runs entirely in one file:

```
AI-Trading-Bot
│
└── index.html
```

All components are included inside the HTML file:

```
index.html
 ├── UI Dashboard
 ├── Chart rendering
 ├── Strategy engine
 ├── Trading engine
 ├── Risk manager
 └── Backtesting system
```

No external backend or database is required.

---

# 🖥 Technologies Used

- HTML
- CSS
- JavaScript
- Chart.js

The entire application runs directly in the browser.

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ai-trading-bot.git
```

Open the project folder:

```bash
cd ai-trading-bot
```

Run the bot by opening:

```
index.html
```

in any browser.

Recommended browsers:

- Chrome
- Edge
- Brave

---

# ⚙ Configuration

Settings can be adjusted inside the HTML code:

- leverage
- risk per trade
- RR ratio
- strategy filters
- trading mode

---

# ⚠ Disclaimer

This project is a **simulation trading environment** and does not execute real trades.

It is intended for:

- learning algorithmic trading
- strategy testing
- trading dashboard experimentation

Trading cryptocurrencies involves risk.

---

# 👨‍💻 Author

AI Trading Bot Project
