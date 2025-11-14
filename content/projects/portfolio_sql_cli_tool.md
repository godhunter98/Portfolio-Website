---
title: "Portfolio Viewer – CLI tool with SQLite + Yahoo Finance"
date: 2025-01-04
---

A **command-line portfolio tracker** that stores holdings in a local **SQLite database** and fetches prices automatically from **Yahoo Finance**.

Originally built as my **CS50 final project**, but designed to be genuinely useful.

### Features

- Add stocks with quantity – price is auto-fetched from Yahoo Finance
- View portfolio in a nicely formatted table using `tabulate`
- See live values in your terminal without opening a browser or Excel

### Tech

- Python
- SQLite (via `sqlite3`)
- `yfinance` for market data
- Clean, argument-based CLI (`portfolio_tool.py`)

This project shows my comfort with **Python, databases, APIs, and building real tools**, not just notebooks.