# 💱 Currency Converter (CLI)

A simple command-line currency converter built in Python that fetches **real-time exchange rates** using the [Frankfurter API](https://frankfurter.dev/). Enter the currencies and amount, and get the converted value instantly.

## 📌 Features

- Fetches live exchange rates (no API key required)
- Converts any amount between two currencies
- Simple and clean CLI interface
- Basic error handling for failed requests

## 🛠️ Tech Used

- Python 3
- [`requests`](https://pypi.org/project/requests/) library
- Frankfurter Exchange Rate API

## 📂 How It Works

1. User enters the currency to convert **from** and **to** (e.g., USD, PKR, EUR).
2. User enters the amount to convert.
3. The app sends a GET request to the Frankfurter API with those currency codes.
4. API returns the current exchange rate in JSON format.
5. The app calculates the converted amount and prints the result.

## 🚀 How to Run

1. Clone this repo or download the script.
2. Install the required library:
   ```bash
   pip install requests
   ```
3. Run the script:
   ```bash
   python currency_converter.py
   ```
4. Enter the currency codes and amount when prompted.

## 💻 Example Usage

```
===== CURRENCY CONVERTER =====
Enter currency to convert from: USD
Enter currency to convert to: PKR
Enter amount: 100

===== CONVERSION RESULT =====
Exchange Rate: 278.45
100.0 USD = 27845.0 PKR
```

## 🌍 Common Currency Codes

| Currency | Code |
|----------|------|
| US Dollar | USD |
| Pakistani Rupee | PKR |
| Euro | EUR |
| British Pound | GBP |
| UAE Dirham | AED |

## 🔧 Future Improvements

- Validate currency codes before sending the request (avoid crashes on typos)
- Show a list of supported currencies to choose from
- Add support for converting multiple amounts at once
- Convert into a GUI app using Tkinter
- Convert into a web API using FastAPI

## 👤 Author

**Muhammad Mustafa Mehtab**
[GitHub Profile](https://github.com/MuhammadMustafaMehtab)
