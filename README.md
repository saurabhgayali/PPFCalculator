# PPF Calculator

An Excel-style Public Provident Fund (PPF) calculator that simulates monthly interest calculations, tracks deposits and withdrawals, and generates a detailed month-wise interest ledger.

Unlike basic PPF calculators, this project provides a spreadsheet-like interface for experimenting with deposit timing, cutoff rules, and different interest crediting methods.

## Features

- 📊 Excel-inspired user interface
- 💰 Deposit & withdrawal ledger
- 📅 Monthly interest calculation
- ⚙️ Configurable PPF cutoff day
- 🔄 Multiple interest crediting modes
  - Annual (PPF Standard)
  - Monthly Compounding
  - Simple Interest Accumulation
- 📈 Live summary dashboard
- 📋 Month-wise interest schedule
- 📤 Export deposit ledger to CSV
- 📤 Export monthly schedule to CSV
- 💾 Automatic LocalStorage persistence
- 📱 Responsive design

## Screens

- Deposit Ledger
- Monthly Interest Schedule
- KPI Dashboard

## How It Works

The calculator simulates PPF interest month by month.

For every month it:

1. Reads all deposits and withdrawals.
2. Applies the configurable cutoff rule.
3. Determines the eligible balance.
4. Calculates monthly interest.
5. Credits interest based on the selected mode.
6. Generates a complete monthly schedule.

This makes it useful for understanding how deposit timing affects returns.

## Configuration Options

- Calculation Date
- Default Interest Rate
- Monthly Cutoff Day
- Deposit Rule
- Interest Crediting Mode

## Tech Stack

- HTML5
- Vanilla JavaScript
- Tailwind CSS
- Font Awesome

No frameworks or build tools are required.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/ppf-calculator.git
```

Open the project:

```text
ppf_calculator.html
```

Or simply double-click the HTML file to launch it in your browser.

## Export

The application supports exporting:

- Deposit Ledger (CSV)
- Monthly Interest Schedule (CSV)

## Data Storage

All data is stored locally in your browser using LocalStorage.

No server or database is required.

## Disclaimer

This project is intended for educational and planning purposes.

Although the calculator follows standard PPF interest rules, always verify calculations with official Government of India notifications or your financial institution before making financial decisions.

## License
CC0
