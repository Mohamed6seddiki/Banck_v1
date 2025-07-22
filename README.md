# Bank Management System

A console-based banking application written in C++ that provides comprehensive client account management and transaction processing capabilities.

## Features

### Client Management
- **Add New Clients**: Create new client accounts with unique account numbers
- **View All Clients**: Display complete client list with account details
- **Find Client**: Search for specific clients by account number
- **Update Client Info**: Modify existing client information
- **Delete Client**: Remove client accounts from the system

### Transaction Operations
- **Deposit**: Add funds to client accounts
- **Withdraw**: Remove funds with balance validation
- **Balance Inquiry**: View individual and total account balances
- **Transaction Confirmation**: User confirmation required for all transactions

### Data Management
- **File-Based Storage**: Persistent data storage using text files
- **Data Validation**: Account number uniqueness and balance checks
- **Safe Operations**: Mark-for-delete system ensures data integrity

## Technical Implementation

- **Language**: C++
- **Data Structure**: Vector-based client records
- **File I/O**: Custom file handling for data persistence
- **User Interface**: Menu-driven console application
- **Data Format**: Delimited text file storage (#//# separator)

## Getting Started

1. Compile the program using any C++ compiler
2. Run the executable
3. Use the menu system to navigate between client management and transactions
4. Client data is automatically saved to `Clients.txt`

## Menu Structure

```
Main Menu
├── Show Client List
├── Add New Client  
├── Delete Client
├── Update Client Info
├── Find Client
├── Transactions
│   ├── Deposit
│   ├── Withdraw
│   ├── Total Balances
│   └── Return to Main Menu
└── Exit
```

## Client Record Structure

Each client record contains:
- Account Number (unique identifier)
- PIN Code
- Full Name
- Phone Number
- Account Balance

Perfect for learning C++ file handling, data structures, and building menu-driven applications.
