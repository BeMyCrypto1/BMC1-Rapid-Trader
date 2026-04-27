# 🚀 BMC1 Rapid Trader

### Bitcoin Manual Trading System with Real-time Data Feed

![Version](https://img.shields.io/badge/version-1.0.0-green)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Python](https://img.shields.io/badge/python-3.11+-yellow)

---

## ✨ Features

| Feature                        | Description                                  |
|--------------------------------|----------------------------------------------|
| 🎮 **Manual Trading Console** | Press `B` to Buy, `S` to Sell, `X` to Exit    |
| 📊 **Live BTC Data Feed**     | Real-time price tracking with 20-line display |
| 💾 **Persistent Storage**     | All trades automatically saved to JSON files  |
| 🖥️ **Retro Terminal UI**      | Clean, professional monochromatic interface   |
| 📈 **Real-time Updates**      | Live BTC price with trend indicators          |
| 🔄 **Session Recovery**       | Resume trading exactly where you left off     |

---

## 📥 Download & Installation

### Option 1: Download EXE (No Python Required)
1. Go to **Releases** section
2. Download `BMC1_Trader.exe` and `BMC1_DataFeed.exe`
3. Place both files in the same folder
4. Double-click to run

### Option 2: Run from Source (Python Required)
        ```bash
                git clone https://github.com/BeMyCrypto1/BMC1-Rapid-Trader.git
                cd BMC1-Rapid-Trader
                pip install requests
                python BMC1_ManualTrader.py

### Option 3: Build EXE Yourself
bash 
        pip install pyinstaller
        pyinstaller --onefile --name "BMC1_Trader" --console BMC1_ManualTrader.py
        pyinstaller --onefile --name "BMC1_DataFeed" --console BMC1_DataFeed.py

     
### 🎮 How to Use
1. Start the Data Feed (Watch Prices)
text
        Double-click: BMC1_DataFeed.exe
        Shows live BTC price updates

* Displays last 20 price movements *

All data saved to data/price_history.json

2. Start the Trader (Execute Trades)
text
        Double-click: BMC1_Trader.exe
                Key	Action
                B	BUY at current price
                S	SELL at current price
                X	Save & Exit

📁 Files Created (Automatic)
text

        BMC1-Rapid-Trader/
                        ├── BMC1_Trader.exe
                        ├── BMC1_DataFeed.exe
                        └── data/
                            ├── trader_state.json      ← Current balance & position
                            ├── trade_history.json     ← Complete trade history
                            └── price_history.json     ← All price feed data

📊 Sample Display
text
    ██████╗ ███╗   ███╗ ██████╗ ██╗
    ██╔══██╗████╗ ████║██╔════╝ ██║
    ██████╔╝██╔████╔██║██║      ██║
    ██╔══██╗██║╚██╔╝██║██║      ██║
    ██████╔╝██║ ╚═╝ ██║╚██████╔╝██║
    ╚═════╝ ╚═╝     ╚═╝ ╚═════╝ ╚═╝

[B] BUY     [S] SELL     [X] EXIT

Balance: $50.00      P&L: $+0.00       ROI: +0.00%
Trades:    0         Win Rate: 0.0%    W/L: 0W/0L
Position: CLOSED

Live Feed: $79123.45    ▲ +12.30 (+0.0155%)

Last Trade: Ready
                ⚠️ First-Time Setup
                When you first run the EXE, Windows SmartScreen may show a warning:

text
Windows protected your PC
Solution:

        Click "More info"
        Click "Run anyway"
        This is normal for new executables. 
        The code is open source and safe.

### 💰 Support the Project
If you find this tool useful, consider supporting development:

        Network	Addresses:

                Polygon/Eth	0x4753BeAa5F9333fa9D8f25d26BE425Ed2D9293a0
                Solana	        Cqzbc6QAvLF7AnETWM3Hj1y4KG87YBCd8LW7MxbEpXw9
                Bitcoin	        bc1qh6vxqxw4lezz5dfxc05ce3q3qw742xenkgzu4s


📋 System Requirements
        Requirement	Specs:  OS Windows 10 or later
        RAM	                128MB minimum
        Storage	                50MB free space
        Internet	        Required for BTC price feed

Python	NOT required (when using the standalone EXE files)
🔄 Version History
        Version	Date	Changes
        v1.0.0	2026-04-27	Initial release

📄 License
MIT License - Free for personal and commercial use

⚡ Quick Start
        Download both EXE files from Releases

        Run BMC1_DataFeed.exe to watch prices

        Run BMC1_Trader.exe to start trading

        Press B to Buy, S to Sell, X to Exit

### Happy Trading! 🎯
