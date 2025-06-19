# 🔍 Overview
This project is a very simple login system, built from scratch, designed for learning purposes. It performs basic username and password authentication, returning a 200 OK status on successful login, and a 401 Unauthorized on failure.

## 🎯 Project Goals
Provide a simple HTTP login endpoint.

No OAuth, no tokens, no sessions.

Return only HTTP status codes (200 OK or 401 Unauthorized).

Follow GDPR principles (user rights, password storage, data minimization).

## 🏗️ Functional Requirements
Login Flow
POST request to /login endpoint.

Accept username and password in the request body (JSON).

Validate credentials against a user database.

On success: Return 200 OK.

On failure: Return 401 Unauthorized.

User Management
Hardcoded user list or simple database storage.

Passwords must be stored hashed (e.g., using bcrypt or Argon2).

Minimal user data storage (GDPR principle).

## 🔒 Security Requirements
Passwords must never be stored in plain text.

All communication must be via HTTPS.

Basic rate limiting to prevent brute force attacks.

## ⚖️ GDPR Compliance Requirements
Data Minimization: Store only username, hashed_password.

Right to Access: Allow users to request their stored data.

Right to be Forgotten: Users can request their account be deleted.

Provide a privacy notice explaining how data is stored and used.
