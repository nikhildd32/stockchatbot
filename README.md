# stockchatbot# Stock Chatbot

Stock Chatbot is a powerful tool that uses OpenAI's GPT-3 model to provide information about stocks. It can fetch the latest stock price, calculate Simple Moving Average (SMA), Exponential Moving Average (EMA), Relative Strength Index (RSI), and Moving Average Convergence Divergence (MACD). It can also plot the stock price for the last year.

## Features

- Get the latest stock price
- Calculate Simple Moving Average (SMA)
- Calculate Exponential Moving Average (EMA)
- Calculate Relative Strength Index (RSI)
- Calculate Moving Average Convergence Divergence (MACD)
- Plot the stock price for the last year

## How to Use

Visit the [Stock Chatbot](https://nikhildd32-stockchatbot-main-0gm63b.streamlit.app/) and enter your query in the text input field. The chatbot will respond with the requested information.

For example, you can ask:

- "What is the latest price for AAPL?"
- "Calculate the SMA for MSFT with a window of 20."
- "Calculate the EMA for GOOGL with a window of 50."
- "Calculate the RSI for FB."
- "Calculate the MACD for TSLA."
- "Plot the stock price for AMZN."

## Code

The code for the Stock Chatbot is written in Python and uses several libraries including OpenAI, pandas, matplotlib, Streamlit, and yfinance. The OpenAI API key is securely stored as a secret in Streamlit.

The main functions in the code are:

- `get_stock_price(ticker)`: Gets the latest stock price for the given ticker.
- `calculate_SMA(ticker, window)`: Calculates the SMA for the given ticker and window.
- `calculate_EMA(ticker, window)`: Calculates the EMA for the given ticker and window.
- `calculate_RSI(ticker)`: Calculates the RSI for the given ticker.
- `calculate_MACD(ticker)`: Calculates the MACD for the given ticker.
- `plot_stock_price(ticker)`: Plots the stock price for the last year for the given ticker.

The chatbot uses OpenAI's ChatCompletion API to generate responses to user inputs. It also uses the `functions` parameter to enable the chat model to call the above functions.

## Try It Out

You can try out the Stock Chatbot [here](https://nikhildd32-stockchatbot-main-0gm63b.streamlit.app/).