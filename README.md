# Automatic Crypto API Data Pulling
![Prise-en-compte-crypto-actifs-dans-politiques-Etat-1440x577](https://github.com/jeanbaptistejacq/Crypto-API-Data-Pulling/assets/80902643/360c989d-47e3-495d-a9bc-08afb979d5f0)
<br/>
<br/>
We build a function to automate the data extraction from the CoinMarketCap Website using the API on Python. Then we proceed by conducting some data exploration and visualization.

## Content

[1. Getting Started](#getting-started)  
&emsp;[1.1 Requirements](#requirements)  
[2. Process of API Pull](#process-of-api-pull)  
[3. Repository Content](#repository-content)  
[4. Function](#function)  
[5. License](#license)  

## Getting Started


We want to pull data through API and read it in a dataset (or in a CSV) looking like this : 
<br/>
<br/>
<img width="700" alt="Captureapi" src="https://github.com/jeanbaptistejacq/Crypto-API-Data-Pulling/assets/80902643/49511342-ed6e-42bf-9111-132b3b881070">

### Requirements

1. Python 3.6+
2. Install Requests **```pip install requests```**
3. Install BeautifulSoup **```pip install beautifulsoup4```**
4. Install Pandas **```pip install pandas```**
5. Get the API URL and the API key (provided within the Jupyter notebook, monthly limited access)

## Process of API Pull

1. Import the required libraries
2. Specify the URL of the API and pass it to **`session.get()`** to pull the data
3. Specify the API key in order to get access to the data
4. Extract the data in JSON in this case

## Repository Content

1. It contains a Jupyter notebook file **`Crypto-API-extraction.ipynb`** with inside the final codes to be used in the project :
    * function to automate the data extraction from the CoinMarketCap website using the API
    * visualizations of coin trends

2. It contains a CSV file **`API.csv`** with inside the data automatically extracted from the website.


## Function

Function to automate the data extraction :

<img width="700" alt="Captureapi2" src="https://github.com/jeanbaptistejacq/Crypto-API-Data-Pulling/assets/80902643/d6cd3098-a67f-44fd-8e30-950f1349af06">
<br/>
<br/>
Here's a chart displaying the percentage variations of several cryptocurrencies over 1 hour, 24 hours, 7 days, 30 days, 60 days, and 90 days : 
<br/>
<br/>
<img width="500" alt="Captureapi3" src="https://github.com/jeanbaptistejacq/Crypto-API-Data-Pulling/assets/80902643/4a3dfeea-4537-4ac2-9ee7-bd06ff69ad75">
<br/>
<br/>
Here's a chart depicting the minute-by-minute price evolution of Bitcoin over a 5-minute interval : 
<br/>
<br/>
<img width="500" alt="Captureapi4" src="https://github.com/jeanbaptistejacq/Crypto-API-Data-Pulling/assets/80902643/1919b8a8-ee2c-4c7c-9336-ee0aed5e3605">
<br/>
<br/>


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
