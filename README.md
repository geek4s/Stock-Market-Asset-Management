# 📊 Stock-Market-Asset-Management
A terminal based stock portfolio & asset management system in C.
This project allows users to buy/sell stocks, view risk-reward ratios, receieve stock alerts, etc.

## 📈 Features: 
- Admin login system
- View all stocks with current prices, low, high, and status
- Buy & Sell stocks (Portfolio tracking)
- Risk-Reward Ratio calculator
- Total portfolio valuation
- Loan eligibility checker
- Toggle stock status between ACTIVE and INACTIVE
- Persistent stock database loaded from txt file

## Tech Stack: 
- Language: C
- File I/O for persistent stock database
- Command-Line interface

## How to RUN: 
```bash
git clone https://github.com/yourusername/stock-management-system.git
cd stock-management-system
```
Create a file stock_database.txt in this format 
```yaml
TCS TataConsultancy 3300.50 3400.00 3200.00 ACTIVE
INFY Infosys 1450.00 1500.00 1400.00 ACTIVE
```

Compile and Run
```bash
gcc main.c -o stock
./stock

