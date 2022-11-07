# PyChain Blockchain Application
You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.


## Instructions:

You’ll make the following updates to the provided Python file for this Challenge, which already contains the basic PyChain ledger structure that you created throughout the module:


* Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

* Change the existing Block data class by replacing the generic data attribute with a record attribute that’s of type Record.

* Create additional user input areas in the Streamlit application. These input areas should collect the relevant information for each financial record that you’ll store in the PyChain ledger.

* Test your complete PyChain ledger.



## Technologies

The project leverages python 3.7 with the following packages:

* [streamlit](https://streamlit.io/) - Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps. So let's get started.

* [Pandas](https://github.com/pandas-dev/pandas) - pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way towards this goal.

* [hashlib](https://docs.python.org/3/library/hashlib.html) -This module implements a common interface to many different secure hash and message digest algorithms. Included are the FIPS secure hash algorithms SHA1, SHA224, SHA256, SHA384, and SHA512 (defined in FIPS 180-2) as well as RSA’s MD5 algorithm (defined in internet RFC 1321). The terms “secure hash” and “message digest” are interchangeable. Older algorithms were called message digests. The modern term is secure hash.




---

## Installation Guide

Clone GitHub Respoitories to yoour local machine

```sh
   git clone https://github.com/jpqt/Challenge-18.git
 ```

Before running the application first install the following dependencies.

```python
pip install Streamlit
```



---

## Usage
![Alt text](https://github.com/jpqt/Challenge-18/blob/main/photo/1.png?raw=true "Testing the bot")
* Enter values for the sender, receiver, and amount, and then click the Add Block button. Do this several times to store several blocks in the ledger.

![Alt text](https://github.com/jpqt/Challenge-18/blob/main/photo/2.png "Testing the bot")

* Verify the block contents and hashes in the Streamlit drop-down menu. Take a screenshot of the Streamlit application page, which should detail a blockchain that consists of multiple blocks. 

![Alt text](https://github.com/jpqt/Challenge-18/blob/main/photo/3.png "Testing the bot")

* Test the blockchain validation process by using the web interface. Take a screenshot of the Streamlit application page, which should indicate the validity of the blockchain.

---

## Contributors


Joshua Pak, taehanpak9@gmail.com

## License

Denver University 2022.
MIT License
