# Joint Savings Application

In this application, I will be automating the creation of a joint savings accounts. 
I create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account.
My smart contract will use ether management functions to implement a financial institution's requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

Overview:
  Here are the steps I took to create the smart contract.
  I define a contract named JointSavings. In this new contract, I define the variables.
  Next, I define a function named "withdraw" that accepts two arguments. In this function I define two "require" statements, and one "if" statement. This makes sure that only the registered recepient can withdraw funds, and only up to the amount that's already in the balance.
  I then define a contract named "deposit", in which I set the contractBalance variable equal to the balance of the contract.
  I also define a function named "setAccount", in which i set addressOne and addressTwo to address1 and address2.
  Finally, I add a fallback function so that the contract can store ether that's sent from outside the deposit function.
  
 ---
 
To view a sample of transactions of the smart contract, I have added a folder named "execution_results" with screenshots of some transactions.

## Technologies

This project leverages Remix.Ethereum.org.

---

## Installation Guide

No installations necce

---

## Usage

Navigate to the directory where fintech_finder.py is located and run the file by typing streamlit run fintech_finder.py in the command line. The user is free to add additional input messages to the code, or make any edits deemed necessary.

---

## Contributors

Just me, and a little bit of help from module 18

## License

no license, feel free to use!


