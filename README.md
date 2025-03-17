# MFA Login System
A simple login system with Multi-Factor Authentication (MFA) using Node.js, Express, MongoDB, and Google Authenticator.

## 🚀 How to Run
1. Clone the repo and install dependencies:
   ```bash
   git clone https://github.com/YOUR_USERNAME/mfa-login-system.git
   cd mfa-login-system
   npm install
   ```
2. Set up your `.env` file with MongoDB and JWT secrets.
3. Start the server:
   ```bash
   node server.js
   ```
4. Use routes for authentication and MFA activation.

## 📌 Endpoints
- `POST /auth/register` - Register user
- `POST /auth/login` - Login user
- `POST /auth/enable-mfa` - Enable MFA for user
- `POST /auth/verify-mfa` - Verify MFA token

Made with ❤️ by [Your Name]