# Joint Savings Application

In this application, I will be automating the creation of a joint savings accounts. 
I create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account.
My smart contract will use ether management functions to implement a financial institution's requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

Overview:
  Here are the steps I took to create the smart contract.
  I define a contract named JointSavings. In this new contract, I define the variables.
  Next, I define a function named withdraw that accepts two arguments. In this funtion a define two require statements, and one if statement. This makes sure that only the registered recepient can withdraw funds, and only up to the amount that's already in the balance.
  I then define a contract named deposit, in which i set the contractBalance varuable equal to the balance of the contract.
  Finally, 

