# Cryptocurrency Wallet

## Package Requirements

`pip install x` where x is the below listed packages:
* `Python == 3.10.6`
* `web3 == 5.31.1`
* `streamlit == 1.13.0`
* `requests == 2.28.1`

## Purpose of Use

Build an application that enables customers to find fintech professionals from among a list of candidates, hire them, and pay them. The application also integrates the Ethereum blockchain network in order to enable customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

## Files Navigation

* `Images`: Directory containing screenshots of Ganache  and Streamlit applications, and headshots of candidates for hire.
* `crypto_wallet.py`: Python file that contains the Ethereum transaction functions. The Python script in this file is also integrated into the KryptoJobs2Go interface program that is found in the `krypto_jobs.py` file.
* `krypto_jobs.py`: Python file that contains the code associated with the web interface of the KryptoJobs2Go application. The code included in this file is compatible with the Streamlit library.

## Solution/Summary

* Import ethereum transaction functions from `crypto_wallet.py` into the KryptoJobs2Go application in `krypto_jobs.py`.

* Sign and execute a payment transaction on KryptoJobs2Go customer interface.
  * Digitally sign a transaction that pays a KryptoJobs2Go candidate, and send this transaction to the Ganache blockchain.

![Choose a Fintech Professional to Hire](https://github.com/lrb924/Cryptocurrency_Wallet/blob/main/Images/Verification.png)

* Inspect the transaction on Ganache.
  * Review the transaction hash code associated with the validated blockchain transaction.

![Transaction Confirmation 1](https://github.com/lrb924/Cryptocurrency_Wallet/blob/main/Images/Transaction1.png)

![Transaction Confirmation 2](https://github.com/lrb924/Cryptocurrency_Wallet/blob/main/Images/Transaction2.png)