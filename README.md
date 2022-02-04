# Fintech Finder Application

About Fintech Finder:
   Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them.
   In this application, I will integrate the Ethereum blockchain network into the application to enable customers to instatly pay the fintech professionals whom they hire with cryptocurrencies.
   
---

## Overview

The steps for this application are broken down as follows:
Import Ethereum Transaction Functions into the fintech finder application.
Sign and execute a payment transaction.
inspect the transaction on Ganache.

I start by importing several functions from the crypto_wallet.py script into the fintech_finder.py file, in order to add wallet operations to the application. 
Within the stramlit sidebar section of the code, I create a variable names account, and set it equel to a call on the generate_account function.
I then define a new st.sidebar.write function to display the balance of the customers account.

Next, I write the code that will calculate a fintech professional’s wage, in ether, based on the worker’s hourly rate and the number of hours that they work for a customer, and write it to the Streamlit sidebar.

To send a transaction, I call the send_transaction function and pass it three paramaters. My Ethereum account information, the candidate_address, and the wage value.

Below are some screeshots of the Streamlit mock block Blockchain.

![screesnhots of Streamlit](https://github.com/chaimkriger/Challenge_19/blob/main/Screenshot%20(80).png)
![screesnhots of Streamlit](https://github.com/chaimkriger/Challenge_19/blob/main/Screenshot%20(81).png)
![screesnhots of Streamlit](https://github.com/chaimkriger/Challenge_19/blob/main/Screenshot%20(82).png)

---

## Technologies

This project leverages Python 3.7, and Streamlit

---

## Installation Guide

Before running this application, Python must be installed. The user can install Streamlit by simply opening the desired enviroment, and typing "!pip install streamlit"

---

## Usage

Navigate to the directory where fintech_finder.py is located and run the file by typing streamlit run fintech_finder.py in the command line. The user is free to add additional input messages to the code, or make any edits deemed necessary.

---

## Contributors

Just me, and a little bit of help from module 18

## License

no license, feel free to use!
