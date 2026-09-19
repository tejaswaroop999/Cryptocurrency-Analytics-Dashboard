# Cryptocurrency Analytics Dashboard

A React dashboard for exploring cryptocurrency market data from the **CoinGecko API**.

The project fetches live Bitcoin market information and presents key metrics and chart-oriented views through a component-based React interface.

## Features

- Fetches cryptocurrency market data from CoinGecko
- Displays current price and market-cap information
- Shows 24-hour high/low and price-change metrics
- Surfaces circulating supply and community data
- Uses reusable React components for cards, charts, and layout
- Uses ApexCharts / React ApexCharts for visualization

## Tech stack

- React 18
- JavaScript
- CoinGecko API
- ApexCharts
- React ApexCharts
- Create React App

## Architecture

```text
React App
  |
  +--> Header
  |
  +--> CardSection
  |     └--> market summary metrics
  |
  +--> ChartSection
        └--> market-cap / volume / price-oriented visualizations

React lifecycle
  |
  v
fetch CoinGecko API
  |
  v
store response in component state
  |
  v
render cards + charts
```

## Data used

The application reads fields such as:

- current USD price
- market-cap change percentage
- all-time high / low values
- 24-hour high / low
- 24-hour price change
- market cap
- total volume
- circulating supply
- Twitter follower count when available

## Run locally

```bash
git clone https://github.com/tejaswaroop999/Cryptocurrency-Analytics-Dashboard.git
cd Cryptocurrency-Analytics-Dashboard
npm install
npm start
```

## Notes

This is an earlier React project and is kept as portfolio evidence of API integration, component-based UI development, and data visualization.

Potential improvements:

- migrate class components to hooks
- support multiple selectable assets consistently
- add loading/error states
- add request caching
- add TypeScript
- add tests for API and visualization flows
- improve responsive chart behavior

## Author

**Teja Swaroop**

- LinkedIn: https://www.linkedin.com/in/tejaswaroop999/
- GitHub: https://github.com/tejaswaroop999
