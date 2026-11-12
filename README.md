# OOP-Practical-10: Custom Exceptions: Banking Transaction

## Purpose & Aim
- **Aim**: To practise reporting application-specific failures and handling different errors in a controlled way.
- **Question**: Create a custom exception hierarchy and throw/catch specific exceptions in a banking transaction program.

---

## What to Do
- Create a BankAccount class with a balance and a withdraw or transfer operation.
- Define custom exceptions such as InsufficientFunds and InvalidAmount, derived from std::exception or a suitable standard exception class.
- Throw InvalidAmount for a non-positive amount and InsufficientFunds when the requested withdrawal exceeds the balance.
- Catch each exception type separately and display a helpful message.
- Test successful and unsuccessful transactions, and make sure a failed transaction does not change the balance incorrectly.
