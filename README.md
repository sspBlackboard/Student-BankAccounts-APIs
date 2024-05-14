# Student-StudentBankAccounts-APIs

## Description

This project involves using Postman to authenticate the API requests for retrieving student bank account details of a student.

## Installation

### Postman

Postman is a collaboration platform for API development. It simplifies each step of building an API and streamlines collaboration, enabling you to create better APIs faster.

To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API List

The `Api_Export.json` file contains the following APIs:

- `GET /ds/campusnexus/StudentBankAccounts`: Returns a list of students bank accounts.
- `GET /ds/campusnexus/StudentBankAccounts({accountId})`: Returns a particular student bank account.
- `GET /ds/campusnexus/StudentBankAccounts/CampusNexus.GetStudentBankAccountDetails(studentId={studentId})`: Returns a particular student bank account of a particular student.
- `GET /ds/campusnexus/StudentBankAccounts/CampusNexus.GetOnlineStudentBankAccount(studentId={studentId})`: Returns a particular online student bank account.
- `POST /api/commands/StudentAccounts/StudentBankAccount/create`: Creates an student bank account.
- `POST /api/commands/StudentAccounts/StudentBankAccount/get`: Get a student bank account details with id.
- `POST /api/commands/StudentAccounts/StudentBankAccount/saveNew`: Save new account details of a student.

## Usage

After importing the `Api_Export.json` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the environment variables correctly:

- `$DOMAIN`: Student Server FQDN
- `$USERNAME`: Your username here
- `$PASSWORD`: Your password here
- `$ACCOUNTID`: Id of the student account
- `$STUDENTID`: Id of the student
