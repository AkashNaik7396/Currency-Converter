# Currency-Converter
💱 Currency Converter Web App

A sleek and easy-to-use Currency Converter built using HTML, CSS, and JavaScript that allows users to convert between different currencies in real-time using exchange rates fetched from a public API. Ideal for learning API integration, DOM manipulation, and responsive UI design.

🚀 Features

🔄 Real-time conversion between 160+ currencies
🌍 Supports all major international currency codes
📱 Responsive design for mobile and desktop
🎨 Clean UI with dropdown selection for currencies
🔎 Instant result update on value or currency change
🌐 Fetches live data from Exchange Rate API (e.g., exchangerate-api or ExchangeRate.host)
🛠️ Technologies Used

HTML5 – Structure and layout
CSS3 – Styling and responsiveness
JavaScript – Logic and dynamic data handling
Public API – Fetching live exchange rates (e.g., https://api.exchangerate.host/latest)
📦 How to Use

Clone this repository
git clone https://github.com/yourusername/currency-converter.git
Open index.html in your browser.
Enter the amount, select From and To currencies, and get the converted value instantly.
🧩 File Structure

currency-converter/
│
├── index.html        # Main HTML structure
├── style.css         # Styling file
├── script.js         # Main JS logic & API handling
└── README.md         # Project overview
🌍 Supported Currency Codes (Samples)

Here are some common ISO 4217 currency codes supported in the converter:

Country	Currency	Code
United States	US Dollar	USD
European Union	Euro	EUR
India	Indian Rupee	INR
United Kingdom	Pound Sterling	GBP
Japan	Japanese Yen	JPY
Australia	Australian Dollar	AUD
Canada	Canadian Dollar	CAD
Switzerland	Swiss Franc	CHF
China	Yuan Renminbi	CNY
Russia	Russian Ruble	RUB
✅ You can easily extend the currency list using any available code in the API response.
📡 Example API Response

Using ExchangeRate.host:

https://api.exchangerate.host/latest?base=USD
Sample JSON output:

{
  "base": "USD",
  "date": "2025-06-25",
  "rates": {
    "INR": 83.12,
    "EUR": 0.91,
    "GBP": 0.78,
    "JPY": 156.5,
    ...
  }
}
✍️ Author

Akash Naik
📧 akashnaik01@gmail.com
🔗 LinkedIn • GitHub

📄 License

This project is licensed under the MIT License – feel free to use and modify.

