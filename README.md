# Currency Converter

This project is a simple currency converter web page that allows users to convert between different currencies in real-time. The app is built using HTML, CSS, and JavaScript, and it fetches real-time exchange rates from an external API.

## Features

- Convert between different currencies with real-time exchange rates.
- Uses an external API for up-to-date currency data.
- Includes a dropdown of country codes mapped to their respective currency codes.
- Simple, user-friendly interface.

## Project Structure

```plaintext
currency-converter/
│
├── index.html        # Main HTML file for the structure of the converter page.
├── style.css         # CSS file for styling the page.
├── app.js            # JavaScript file containing the logic for fetching data from the API and handling conversions.
├── codes.js          # JavaScript file that contains country codes mapped to their currency codes.
└── README.md         # Project documentation.
```

## API

- The application fetches real-time exchange rates from the following API base URL: https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies
- You can find more details about the API on the [Github Repository](https://github.com/fawazahmed0/exchange-api)

## How it Works

1. Users select the currencies they want to convert from and to, using the dropdown menus.
2. Input the amount to convert.
3. The app fetches the latest exchange rate using the currency API.
4. The converted amount is displayed to the user.

## How to Run

1. Clone or download this repository to your local machine.
2. Open the index.html file in your web browser.
3. Use the currency converter by selecting currencies and entering an amount.

## Future Enhancement Ideas

- Implement error handling for failed API calls or network issues.
- Provide a historical exchange rate feature.
