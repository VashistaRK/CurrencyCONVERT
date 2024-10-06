# Currency Converter Web App

## Overview
This is a simple **Currency Converter** web application that allows users to convert an amount from one currency to another. It utilizes the **@fawazahmed0 currency API** to get the latest exchange rates between currencies. The application also dynamically updates country flags based on the selected currencies.

## Features
- Convert any amount between two different currencies using live exchange rates.
- Prevents invalid input by setting the minimum conversion amount to 1.
- Default currencies are set to **USD** (United States Dollar) for "from" and **INR** (Indian Rupee) for "to".

## How it Works
1. The app fetches live exchange rates from the **Currency API** provided by [@fawazahmed0](https://github.com/fawazahmed0/currency-api).
2. When a user selects a currency from the dropdown menu, the respective country’s flag is shown next to the dropdown.
3. The user can enter an amount in the "from" currency, and upon clicking the button, the app calculates the equivalent amount in the "to" currency based on the current exchange rate.
4. The result is displayed as a message in the format:  
   `<amount> <from_currency> = <converted_amount> <to_currency>`.

## API Endpoints:
- **Currency API Base URL**:  
  `https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies`
  
- **Flags API Base URL**:  
  `https://flagsapi.com/[country_code]/flat/64.png`

## Setup Instructions
1. **Clone the repository**:  
   ```bash
   git clone <repository-url>
