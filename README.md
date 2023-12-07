# Computer_Networks_Project-Sem-III


# Banking Management System

## Overview

Welcome to the Banking Management System project, a comprehensive simulation of banking operations implemented in the C programming language. This project aims to provide hands-on experience in various LINUX concepts, including socket programming, process management, file management, record locking, system calls, shared memory, signals, and more.

## Project Files

1. **add_admin.c**: Run to add an admin user with privileged access.
2. **count_initial.c**: Execute to initialize the Account Number (default: 1000).
3. **tserver.c**: Run to start the server, waiting for client connections.
4. **tclient.c**: Execute to connect a client user to the server.
5. **viewAdmin.c**: Used to view details of an admin user.

## How to Run the Project

1. Compile and run `count_initial.c` to initialize the Account Number.
2. Compile and run `tserver.c` to start the server.
3. Compile and run `tclient.c` to connect a client user to the server.
4. To add an Admin user, compile and run `addAdmin.c`.

## Project Functionalities

### Basic Online Banking System Features

1. **Creating an Account:**
   - Normal Account
   - Joint Account
   - Admin Account

2. **Operations on an Account:**
   - Deposit Money
   - Withdraw Money
   - View Account Details
   - Change Password
   - Transfer Money

3. **Admin Account:**
   - Admins can add, delete, and view any account.
   - Special permissions for admin account holders.

### Account Types

1. **Normal Account (Single User):**
   - Create an account with user details.
   - Login using credentials.
   - Perform various operations, including viewing details, depositing and withdrawing money, changing passwords, checking balances, transferring money, and exiting.

2. **Joint Account (Two Users):**
   - Create an account with details for two users.
   - Login using credentials.
   - Simultaneous operations for both users, including viewing details, depositing and withdrawing money, changing passwords, and exiting.

3. **Admin Account (Root User):**
   - Create an admin account with special permissions.
   - View any account details using the account number.
   - Delete normal and joint accounts.
   - Create new accounts with assigned account numbers.
   - Exit the admin interface.

## Learning Objectives

This project offers a hands-on learning experience in system-level programming concepts and provides a robust simulation of a banking environment. Feel free to explore and enhance the project further!
