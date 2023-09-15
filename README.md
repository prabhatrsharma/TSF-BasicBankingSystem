# The Sparks Foundation - Basic Banking System

## Index
- [Description](#Description)
- First Time Installation
- How To Run
- Screenshot

## Description
- This a Internship project by Sparks Foundation.
- This project is built on HTML/CSS, Bootstrap, PHP and MySQL.
- Details of Customers are maintained as `Name`, `Email`, `Current_Balance` are fields.
- Transaction is done through PDO, If some Error occured while Transaction changes made to table is Rollback(Reverted).  

## First Time Installation
- Clone the Repository.
- Make sure you have installed XAMP on your computer.
- Copy this folder(Sparks-Foundation) to XAMPP installation Directory and then inside htdocs folder.

```
For Example
C:\xampp\htdocs\
```
- Open Xamp Control Panel. Click on Start button near Apache and MySQL.
- Open browser type the following into search bar.
```
http://localhost/TSF-BasicBankingSystem/landingPage.php
```
- If everything works fine you would see landing page in browser.

## How To Run
- After following steps above(First Time Installation).
- Make Sure XAMP is active with Apache and MySQL Server Enabled.
- Open Browser Enter the following URL:
```
http://localhost/TSF-BasicBankingSystem/
```
OR
```
http://localhost/TSF-BasicBankingSystem/landingPage.php
```
- You will land to Homepage of TSF Bank Website.
- Click On `View Customers` from Navigation OR `View Customers` button for viewing detail of all Customers.
- You will see Customer details in table with deatils like(Account Number, Name, Email, Current balance, etc.).
- Click on `Transact` Button Corresponding Any row of table.
- Now We are on Money Transfering Page. Select a Sender at `Transfer from` and confirm the Selected sender by writing his/her account number at the `Confirm Sender` and same at the `Transfer To` and `Confirm Receiver` on other side and also Enter Transfer Amount, and finally Click on `Make Transfer` Button To Start Transfer.
- Make sure the Amount you enter is not greater than current balance of the Person Selected, else it will give message accordingly.
- If the Transaction is successful Message will displayed and Changes made by above Transaction will be updated to `transaction_history` table. 