# Python Currency Converter
The Python Currency Converter is a simple script that allows users to convert currency from one currency to another using the exchange rates provided by the apilayer Currency Exchange Rates API.

## Features:
Currency Conversion: Users can specify the source currency, the target currency, and the amount to convert.

Real-time Exchange Rates: The script retrieves real-time exchange rates from the apilayer Currency Exchange Rates API to perform currency conversion.

## How to Use:
Installation: Ensure you have Python installed on your system. If not, download and install it from python.org.

Obtain API Access Key: Obtain an API access key from apilayer Currency Exchange Rates API to use in the script.

Download the Script: Clone or download the Python currency converter script to your local machine.

Run the Script: Open a terminal or command prompt, navigate to the directory containing the script, and execute it using Python:

```
python currency_converter.py
````

Follow Prompts: The script will prompt you to enter the API access key, source currency, target currency, and the amount to convert.

1. Enter your API access key when prompted.
2. Enter the currency you want to convert to (e.g., EUR, GBP, JPY).
3. Enter the source currency (e.g., USD, EUR, GBP).
4. Input the amount you want to convert.
5. The converter will fetch the latest exchange rates and display the converted amount.

Currency Conversion: The script will then retrieve the real-time exchange rate and perform the currency conversion, displaying the converted amount.

Example:

```
API Anahtarını Giriniz: [Your API Access Key]
Dönüştürülecek Para Birimini Griniz: EUR
Kaynak Para Birimini Giriniz: USD
Miktar: 100

Para Döviz Kuru: 83.09
```

## Requirements
requests: Python library for making HTTP requests.

Install dependencies using pip:
```
pip install requests
```

## Security Considerations:
Keep your API access key secure and avoid sharing it publicly or storing it in plain text.

Only use reputable and trustworthy currency exchange rate APIs.



