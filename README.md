# Ethereum_Payments_Application

This application is a marketplace where FinTech professionals can list their services and their hourly rate; persons looking to hire these professionals can pay them in Ether. It uses a private blockchain through Ganache for testing purposes, but could easily be connected to any of Ethereum's testnets, or their mainnet.

![functioning_app](https://github.com/rrmangum/Ethereum_Payments_Application/blob/main/Images/Functioning_App.png?raw=true)

## Validated Transactions

![Amount_Sent_Proof](https://github.com/rrmangum/Ethereum_Payments_Application/blob/main/Images/Ganache_Amount_Sent_Proof.png?raw=true)

![Sent_Transaction](https://github.com/rrmangum/Ethereum_Payments_Application/blob/main/Images/Ganache_Sent_Transaction_Proof.png?raw=true)

![Account_Balance](https://github.com/rrmangum/Ethereum_Payments_Application/blob/main/Images/Ganache_Account_Balance_Proof.png?raw=true)
---

## Technologies

This analysis uses python Python and the following libraries:
* [dataclass](https://docs.python.org/3/library/dataclasses.html) - Provides a decorator and functions for automatically adding generated special methods.
* [Typing](https://docs.python.org/3/library/typing.html) - Provides runtime support for type hitns
* [streamlit](https://streamlit.io/) - Provides a Python library for easily creating frontend applications
* [web3](https://web3py.readthedocs.io/en/v5/) - A Python library for interacting with Ethereum
* [Requests](https://requests.readthedocs.io/en/latest/) - A Python HTTP library
* [dotenv](https://github.com/theskumar/python-dotenv) - Reads key-value pairs from a .env file and sets them as envrionment variables
* [bip44](https://github.com/kigawas/python-bip44) - Python support for Bitcoin Imrpovement Proposal 44

---

## Installation Guide

1. Download [Anaconda](https://www.anaconda.com/products/distribution) to your computer. 

2. Download [Ganache](https://trufflesuite.com/ganache/) to your computer.

3. Clone the repo to your local machine

4. Navigate to the directory of the cloned repo in your terminal or gitbash

5. Run the following command in your terminal or gitbash:
```python
pip install -r requirements.txt
```
6. Open Ganache and click quickstart. Copy the mnemonic phrase that is provided. Paste the mnemonic phrase into your own .env file like so:
```python
MNEMONIC = "<YOUR_SEED_PHRASE>"
```
MAKE SURE YOU LEAVE GANACHE RUNNING OR THE APPLICATION WILL NOT FUNCTION CORRECTLY

7. Run the following command in your terminal or gitbash:
```python
streamlit run fintech_finder.py
```
---

## Contributors

Ryan Mangum - [LinkedIn](https://www.linkedin.com/in/ryanrmangum/) | rrmangum@gmail.com

---

## License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) [2022] [Ryan Mangum]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.