# ATM_EXERCISE
<h1>ATM Machine React App </h1>
</br>
<p> This is a simple React application that simulates an ATM machine. The application allows users to select between making a deposit or a cash back transaction, enter the transaction amount, and view their account balance.</p>
<br/>
<h2>Components</h2>
<h3>ATMDeposit:</h3>
<p>
This component is responsible for displaying the deposit or cash back form based on the user's selection. It takes in three props:
onChange: a function that is called whenever the user enters a deposit amount.
isDeposit: a boolean value that determines whether the user has selected the deposit or cash back option.
isValid: a boolean value that determines whether the user has entered a valid amount for the transaction.
</p>
<h3>Account:</h3>
<p>
This component is the main component of the application. It is responsible for managing the state of the application and rendering the user interface. It consists of the following state variables:

deposit: the amount of the transaction.
totalState: the total balance of the account.
isDeposit: a boolean value that determines whether the user has selected the deposit or cash back option.
atmMode: a string value that represents the user's selection (either "Deposit" or "Cash Back").
validTransaction: a boolean value that determines whether the user has entered a valid amount for the transaction.
The Account component also contains the following methods:

handleChange: a method that is called whenever the user enters a deposit amount. It validates the amount entered and updates the state accordingly.
handleSubmit: a method that is called when the user submits the form. It updates the account balance based on the transaction type and amount entered.
handleModeSelect: a method that is called when the user selects a transaction type. It updates the state based on the user's selection.
</p>

<h2>License</h2>
<p>
  This project is licensed under the MIT License. See the LICENSE file for more information.
  </p>
