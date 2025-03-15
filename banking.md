# Banking System Case Study

## Problem Statement
Design an object-oriented banking system that supports multiple account types, allows customers to perform various banking operations, calculates interest, applies fees, and maintains transaction history.

## System Requirements
1. **Customer Management**:
   - Store customer personal information
   - Track customer accounts and relationships
   - Support joint accounts

2. **Account Types**:
   - Checking accounts with debit cards
   - Savings accounts with interest
   - Money market accounts
   - Certificates of deposit (CDs)

3. **Banking Operations**:
   - Deposits and withdrawals
   - Fund transfers between accounts
   - Bill payments
   - Account statements

4. **Financial Calculations**:
   - Interest calculations for different account types
   - Fee assessment based on account status
   - Overdraft handling

5. **Security**:
   - Authentication and authorization
   - Transaction validation
   - Audit trail for all operations

## Classes and Relationships

**Customer-related Classes:**

**Account-related Classes:**

**Transaction-related Classes:**

**Banking Service Classes:**

## Key OOP Concepts to Identify

1. **Inheritance**: Person → Customer, Account → CheckingAccount/SavingsAccount
2. **Abstract Classes**: Account is an abstract base class
3. **Encapsulation**: Private account balances with controlled access
4. **Polymorphism**: Different account types implement interest calculation differently
5. **Interfaces**: Transaction processing interfaces
6. **Composition**: Bank contains Accounts, Accounts contain Transactions
