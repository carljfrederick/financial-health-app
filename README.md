# Financial Health App

The Financial Health application can be used by financial instituions as a tool to assist clients with visualizing their current savings and determine if they have enough reserves for an emergency fund. In addition, the tool is used to forecast the performance of a client's retirement portfolio to make calculated predictions about their long-term financial future. The tool leverages use of the Alpaca SDK to make Alpaca API calls to obtain historical price data for the use of creating Monte Carlo simulations. This instrument can provide wealth managers a portfolio construction solution to build diverse portfolio models for their clients.

---

## Technologies

This application leverages Python 3.7 with the following libraries and dependencies:

Pandas: Python library for data analysis and manipulation

OS: Interacting with the computer's operating system

Requests: HTTP Python library used to access data via APIs

JSON: Python library for storing and exchanging data via an API

python-dotenv: Library used to read key-value pairs from an environment file (.env) 

alpaca-trade-api: Alpaca SDK used to interact with the Alpaca API

MCForecastTools: Library that contains the Python code used to run the Monte Carlo Simulation

Matplotlib (%matplotlib): Python library for creating visualizations 


## Installation Guide

Pandas is included in the Anaconda open source distribution. You may download Anaconda for your operating system here: https://www.anaconda.com/products/individual. After installing Anaconda, follow the Pandas installation instructions here: https://pandas.pydata.org/getting_started.html. 

OS is a standard library included with Python

Requets and JSON libraries are included in the Anaconda open source distribution and ready for use after Anaconda installation

Install the python-dotenv library using the pip command in a terminal: pip install python-dotenv

Install the Alpaca SDK running the following command in a terminal: pip install alpaca-trade-api

The MCForecastTools library exists as a Python file MCForecastTools.py located in the folder structure

Install the matplotlib library using the pip command: pip install matplotlib

---

## Usage

Go to the Alpaca signup site at https://app.alpaca.markets/signup to generate Alpaca API credentials. Account signup is free! Once signup is completed, you will generate two keys: the API Key ID and a secret key. Copy these keys to an environment (.env) file located in inside the project folder structure to protect them. The operating system will hide the .env file inside this folder structure.

To use the Financial Health application, clone the repository and run the financial_planning_tools.ipynb

---

## Contributors

Contributions by Carl Frederick.

---

## License

MIT.
