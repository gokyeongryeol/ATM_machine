# ATM machine

This repository contains notebook implementations of the atm machine with python3.

## Process summary

The whole process goes as follows:

1. The language option for the atm machine is set among English and Korean.
2. A card is created with an ID and a pin. Such card can handle multiple accounts where we set the number of accounts to be 3 by default.
3. Accounts are created with their unique IDs and balances.
4. The card with multiple accounts is inserted to the atm machine. Since then, one can eject the card anytime. As the card is ejected, one should create a new card to insert it into the atm machine.
5. To access the accounts within the card, one should enter the correct pin number. After the 5 wrong trials, the card is permanantly blocked from using the atm machine. Then, one should create a new card with a new ID that is not registered at the black list of the atm machine.
6. As one is authorized to access to the accounts, the account index to view is entered. The index should be chosen among 1 to the number of accounts connected to the card(=3 by default). Since then, one can easily switch to other account by entering another index.
7. With the chosen account, one could see balance, deposit, and withdraw. Note that the amount of withdrawl is limited to be less than or equal to the amount of balance.

## Quick run

The easiest way to run the code is to run it in the browser on [Colab](https://colab.research.google.com/drive/1-eud4LRyPo5JpkBnn33OvXAb_ZuJag5Q?usp=sharing).

Colaboratory is a free Jupyter notebook environment provided by Google that requires no setup and runs entirely in the cloud. The hosted runtime already includes python 3.7.13.

## Contact

Any feedback is much appreciated! Drop me a line at kyeongryeol.go@gmail.com.