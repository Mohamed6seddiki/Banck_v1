Bank Management System<br>
A comprehensive console-based bank management application built in C++ for managing client accounts and banking operations.<br>
##
📋 Features<br><br>

Client Management: Complete CRUD operations for bank clients<br>
Account Operations: Create, view, update, and delete client accounts<br>
Data Persistence: File-based storage system using text files<br>
Interactive Menu: User-friendly console interface with menu navigation<br>
Input Validation: Robust error handling and input validation<br>
Account Security: PIN code protection for client accounts<br><br>
##
🔧 Core Functionality<br>
Main Operations<br><br>

List Clients: Display all registered clients in a formatted table<br>
Add New Client: Register new clients with account validation<br>
Delete Client: Remove clients with confirmation prompts<br>
Update Client Info: Modify existing client information<br>
Find Client: Search for specific clients by account number<br>
Exit: Clean program termination<br><br>

Client Data Management<br><br>

Account Number (unique identifier)<br>
PIN Code (security)<br>
Full Name<br>
Phone Number<br>
Account Balance<br><br>
##
🏗️ Technical Architecture<br>
Key Components<br><br>

Data Structure: Custom sClient struct for client information<br>
File I/O: Text file-based data persistence (Clients.txt)<br>
String Processing: Custom string splitting and parsing functions<br>
Menu System: Enum-based menu navigation
Input Handling: Comprehensive input validation and error checking

File Format
Uses a custom delimiter-based format (#//#) for storing client data:
AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance
