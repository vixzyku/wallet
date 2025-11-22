# Crypto Wallet Website

A fully functional cryptocurrency wallet web application with user authentication and wallet management.

## Features

- **User Authentication**
  - Sign up with username, email, and password
  - Sign in with username and password
  - Secure session management

- **Wallet Management**
  - Automatic wallet generation on sign up
  - View wallet address and balance
  - Send transactions
  - Receive funds (display wallet address)
  - Transaction history

- **Security**
  - Password hashing with bcrypt
  - Session-based authentication
  - Encrypted private key storage

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Open your browser and navigate to:
```
http://localhost:5000
```

## Project Structure

```
Wallet/
├── app.py                 # Flask backend application
├── requirements.txt       # Python dependencies
├── templates/            # HTML templates
│   ├── index.html       # Sign in page
│   ├── signup.html      # Sign up page
│   └── dashboard.html   # Main wallet dashboard
├── static/              # Static files
│   ├── css/            # Stylesheets
│   │   ├── style.css   # Main styles
│   │   └── dashboard.css # Dashboard styles
│   └── js/             # JavaScript files
│       ├── auth.js     # Authentication logic
│       └── dashboard.js # Dashboard functionality
└── crypto_wallet.db    # SQLite database (created on first run)
```

## Database Schema

- **User**: Stores user account information
- **Wallet**: Stores wallet addresses and encrypted private keys
- **Transaction**: Stores transaction history

## Notes

- This is a demonstration wallet. In production, implement proper key encryption and blockchain integration.
- Private keys are currently stored in plain text (encrypted) for demonstration purposes.
- The application uses SQLite for simplicity but can be upgraded to PostgreSQL for production.

"# crypto-wallet" 
"# wallet" 
"# wallet" 
