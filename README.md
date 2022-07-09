# Cryptocurrency-Wallet

## Goals
`fintech_finder.py`: the code associated with the web interface of the application.
`crypto_wallet.py`: the Ethereum transaction functions. `crypto_wallet.py` Python scripts are integrated into the Fintech Finder interface program that is found in the `fintech_finder.py` file.

### Integrating these two files will allow you to automate the tasks associated with...
* generating a digital wallet
* accessing Ethereum account balances
* signing and sending transactions via a personal Ethereum blockchain, Ganache.

### Assume the perspective of a Fintech Finder customer in order to do the following:
* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.
* Fetch and display the account balance associated with your Ethereum account address.
* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.
* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.
* Review the transaction hash code associated with the validated blockchain transaction.

Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details.