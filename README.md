# Bankist App

A minimalist online banking interface with secure user authentication and core banking features.

## Features

- **User Authentication**: Secure login system with username and PIN
- **Transaction History**: View detailed history of deposits and withdrawals
- **Money Transfers**: Transfer money between accounts
- **Loan Requests**: Request loans based on account criteria
- **Account Management**: Close account functionality
- **Auto-logout Timer**: Security feature that logs out inactive users
- **Transaction Sorting**: Sort transactions by amount
- **Balance Overview**: View current balance with incoming and outgoing transaction summaries

## Demo Accounts

To test the application, use these demo accounts:

1. **Account One**

   - Username: vm
   - PIN: 1111
   - Type: Premium

2. **Account Two**
   - Username: jd
   - PIN: 2222
   - Type: Standard

## Usage

1. **Login**

   - Enter username and PIN
   - Click arrow button or press Enter

2. **Transfer Money**

   - Enter recipient's username
   - Enter amount
   - Click transfer button

3. **Request Loan**

   - Enter loan amount
   - Click request button
   - Loan is granted if you have deposits ≥ 10% of requested amount

4. **Close Account**
   - Enter your username and PIN
   - Account will be permanently deleted

## Technical Details

- Built with vanilla JavaScript
- Uses modern ES6+ features
- Implements array methods and DOM manipulation
- Handles dates and timers
- Responsive design with CSS Grid and Flexbox

## Security Features

- Auto-logout after 2 minutes of inactivity
- PIN-protected access
- Session management
- Secure transfer verification

## Note

This is a demo project and doesn't involve real money transactions. It's built for educational purposes to demonstrate modern JavaScript features and DOM manipulation.
