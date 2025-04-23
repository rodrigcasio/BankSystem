# BankSystem
A C++ program simulating bank accounts with deposists, withdrawals, transfers, and interest calculations.

## Features
-  Create acccounts with initial balances and interest rates.
-  Perform transfers (e.g., $2000 from "1010" to "1012").
-  Track transaction histories.
-  Apply interest to savings acounts (2% for #1010, 9% for #1012).

## Files 
-  'mainBankAccount.cpp' : Main program logic.
-  'h_BankAccount.hpp' : Account class header.
-  'fns_BankAccount.cpp' : Account and transaction methods.
-  'classBank.hpp' : Bank class for account management.

# Sample Output 
Account #1010: $1203.60
Account #1011: $5490.00
Account #1012: $10580.63

## How to run
```bash
g++ mainBankAccount.cpp fns_bankAccount.cpp classBank.hpp -o bank
./bank
