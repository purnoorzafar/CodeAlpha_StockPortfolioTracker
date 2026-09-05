# 📈 CodeAlpha Stock Portfolio Tracker

A simple and user-friendly **Stock Portfolio Tracker** developed as part of the **CodeAlpha Python Programming Internship — Task 2**.

The project allows users to enter stock symbols and quantities, calculates the investment value using predefined stock prices, displays the portfolio through a professional dashboard, and saves the portfolio data into a CSV file.

---

## 🎯 Project Objective

The main objective of this project is to build a simple stock portfolio tracking system using Python.

The application calculates the total investment based on:

**Stock Price × Quantity = Investment Value**

The project uses manually defined stock prices through a Python dictionary, as required by the CodeAlpha internship task.

---

## ✨ Features

* 📊 Display available stocks and their predefined prices
* 🔢 Enter stock symbols and quantities
* 💰 Calculate individual investment values
* 📈 Calculate total portfolio investment
* 📦 Calculate total shares
* 📋 Display entered stocks in a professional dashboard
* 📊 Show number of stock holdings
* 💵 Calculate average holding value
* 📁 Export portfolio information to a CSV file
* ⚠️ Validate incorrect stock symbols
* ⚠️ Validate invalid or negative quantities
* 💻 Beginner-friendly Python implementation

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **HTML**
* **CSS**
* **CSV File Handling**
* **Python Dictionary**
* **Python Lists**
* **Loops**
* **Conditional Statements**
* **Exception Handling**

---

## 📌 Predefined Stock Prices

The project uses a manually defined dictionary containing stock symbols and prices.

Example:

```python
stock_prices = {
    "AAPL": 180,
    "TSLA": 250,
    "GOOGL": 140,
    "MSFT": 420,
    "AMZN": 175,
    "META": 500,
    "NFLX": 650,
    "NVDA": 120
}
```

These prices are **sample/hardcoded values** and are not live market prices.

---

## 🧮 How It Works

The application follows these basic steps:

### 1. Display Available Stocks

The program displays the available stock symbols and their predefined prices.

### 2. Enter Stock Symbol

The user enters a stock symbol such as:

```text
AAPL
```

### 3. Enter Quantity

The user enters the number of shares:

```text
5
```

### 4. Calculate Investment

The application calculates:

```text
Stock Price × Quantity
```

For example:

```text
AAPL Price = $180
Quantity = 5

Investment = $180 × 5
Investment = $900
```

### 5. Add More Stocks

The user can continue entering different stocks.

### 6. Finish Input

The user types:

```text
done
```

to finish entering portfolio data.

### 7. Display Dashboard

The application generates a professional dashboard containing:

* Total Investment
* Stock Holdings
* Total Shares
* Average Holding Value
* Portfolio Details

### 8. Save Data to CSV

The portfolio information is saved into:

```text
my_stock_portfolio.csv
```

---

## 📊 Dashboard

The dashboard provides a visual summary of the entered portfolio.

It displays the following information:

| Information           | Description                            |
| --------------------- | -------------------------------------- |
| Total Investment      | Total value of all stocks              |
| Stock Holdings        | Number of stock entries                |
| Total Shares          | Total number of shares                 |
| Average Holding Value | Average value per holding              |
| Portfolio Details     | Stock, quantity, price and total value |

---

## 📁 CSV Output

The project also saves the portfolio information into a CSV file.

Example:

```text
Stock,Quantity,Price,Total Value
AAPL,5,180,900
TSLA,2,250,500
MSFT,3,420,1260
```

The CSV file can be opened using **Microsoft Excel, Google Sheets, or other spreadsheet software**.

---

## 🗂️ Project Structure

```text
CodeAlpha_StockPortfolioTracker/
│
├── Stock_Portfolio_Tracker.ipynb
├── my_stock_portfolio.csv
└── README.md
```

### Files Description

**Stock_Portfolio_Tracker.ipynb**
Contains the complete Python code, user input system, calculations, dashboard and
