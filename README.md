#
Ethereum Blockchain

# Module 19 - Ethereum Blockchain


## Challenge: 

What You're Creating
To complete this Challenge, you will use two Python files, both of which are contained in the starter folder.

The first file that you will use is called fintech_finder.py. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.

The second file that you will use is called crypto_wallet.py. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file.

Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, you will assume the perspective of a Fintech Finder customer in order to do the following:

Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

Fetch and display the account balance associated with your Ethereum account address.

Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

Review the transaction hash code associated with the validated blockchain transaction.

Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.



     

#
[<img src="https://img.shields.io/badge/language-Python-orange.svg?logo=LOGO">](https://www.python.org/)
[<img src="https://img.shields.io/badge/platform-dev-orange.svg?logo=LOGO">](<LINK>)
[<img src="https://img.shields.io/badge/libraries-5-orange.svg?logo=LOGO">](<LINK>)
[<img src="https://img.shields.io/badge/license-GNU General Public License v3.0-blue.svg?logo=LOGO">](COPYING.txt)


---

## Technologies

*The Imports required for the program to run are as follows:*

### Languages:   

### [Python](python.org)

### Import the required libraries and dependencies

>`streamlit`         https://streamlit.io/

>`dataclasses`       https://docs.python.org/3/library/dataclasses.html

>`typing`            https://docs.python.org/3/library/typing.html

>`Web3`              https://web3py.readthedocs.io/en/stable/

>`hashlib`           https://docs.python.org/3/library/hashlib.html




---

## Usage



* Instructions

    * Open the pychain.py file that is included in the repository. You’ll use this file to complete the steps for this Challenge. Notice that the PyChain ledger that you built throughout this module already includes the functionality to create blocks, perform the proof of work consensus protocol, and validate blocks in the chain.

    * The steps for this challenge are broken out into the following sections:

        * Import Ethereum Transaction Functions into the Fintech Finder Application
  
        * Sign and Execute a Payment Transaction
  
        * Inspect the Transaction on Ganache
  




* Requirements
    
    * Import Ethereum Transaction Functions into the Fintech Finder Application 

        * Import generate_account, get_balance, and send_transaction from the crypto_wallet.py file. 

            * Call the generate_account function and store the account object. 

            * Call the get_balance function and pass it the Ethereum account.address. 

        * Sign and Execute a Payment Transaction 
            
            * Calculate the transaction’s total wage. 

            * Call the send_transaction function and pass it the account, candidate_address, and wage parameters. 

            * Return the transaction hash from the send_transaction and display it on the application’s web interface. 

        * Inspect the Transaction on Ganache 

            * Send a transaction using the Fintech Finder app, and then use the returned transaction hash to verify the transaction oin Ganache. On the top left corner of the Ganache   application there is a button labeled "Accounts", next to it there is one labeled "Blocks", then one labeled "Transactions". Click the "Transactions" button to view the recent transactions. 

            * In your README.md file, provide screenshots from Ganache that show the sender’s address balance and history, and the recipient's address balance and history. 
           
           


>
>
> Challenge Available at:
https://courses.bootcampspot.com/courses/1251/assignments/25283?module_item_id=512378


## Working App Video and Screenshots

* Address Balance and History 





* Recipient's Address Balance and History





* Transaction Details 





## Contributors

Scott J. Marler


> ### LinkedIn Profile:     [https://www.linkedin.com/in/scott-marler-212040b6/](https://www.linkedin.com/in/scott-marler-212040b6/)



---

## Licenses

> [GNU General Public License v3.0](COPYING.txt)
