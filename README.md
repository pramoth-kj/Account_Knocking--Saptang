# Account Knocker

The Account Knocker is a Python script that uses Selenium and BeautifulSoup to check the presence of an email address on various online platforms such as Pinterest, Spotify, and Quora. The script interacts with the web pages, captures relevant information, and writes the results to an output file.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Results](#results)
- [Script-Details](#script-details)
- [Disclaimer](#disclaimer)

## Prerequisites

- Python 3.x
- Selenium
- ChromeDriver
- BeautifulSoup

Install the required dependencies using:

pip install selenium beautifulsoup4

Download ChromeDriver from `https://sites.google.com/chromium.org/driver/` and ensure it's in your system's PATH.

## Usage

Before running the script, make sure you have the required dependencies installed. You can install them using the following command:

Results
The script will generate an output.txt file containing the results of the account checks. Each line in the file corresponds to the status of an email address for a specific platform.

## Results

The script generates a detailed report on the presence of each email address on different platforms. The results are categorized as follows:

`Pinterest: "✔" indicates the email exists on Pinterest, and "❌" indicates it does not.`

`Spotify: "✔" indicates the email exists on Spotify, and "❌" indicates it does not.`

`Quora: "✔" indicates the email exists on Quora, and "❌" indicates it does not. `

## Script-Details

The script utilizes Selenium to interact with web pages and BeautifulSoup for HTML parsing. It checks the existence of each email address on Pinterest, Spotify, and Quora and records the results in a structured format.

## Disclaimer

This script is provided for educational and informational purposes only. Use it responsibly and ensure compliance with the terms of service of the respective platforms. The authors are not responsible for any misuse or violation of terms.
