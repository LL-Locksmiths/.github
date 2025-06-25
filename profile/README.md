# 🗝Locksmiths

A lightweight, developer-friendly OAuth 2.0 server built in JavaScript.  
Designed for modern applications that require secure token-based authentication, including Access and Refresh Tokens, Client registration, and Authorization Code flow with PKCE.

# 🚀 Features
- ✅ User Registration & Login
- ✅ Access Token (JWT/Opaque) Issuance
- ✅ Refresh Token Support
- ✅ Authorization Code Flow with PKCE
- ✅ Client Application Registration
- ✅ Scope & Permission Management
- ✅ Token Introspection & Validation
- ✅ Token Revocation Endpoint
- ✅ Optional Session Management
- ✅ OAuth 2.0 Standards Compliance

# 🔒 Security Requirements
Passwords must never be stored in plain text.

All communication must be via HTTPS.

Basic rate limiting to prevent brute force attacks.


# ⚖️ GDPR Compliance Requirements
Data Minimization: Store only username, hashed_password.

Right to Access: Allow users to request their stored data.

Right to be Forgotten: Users can request their account be deleted.

Provide a privacy notice explaining how data is stored and used.

# 👨‍💻 Code Requirements
There must be a clear definition of a good design pattern.

It must follow the SOLID principles at least.

Prefer the UseCase pattern but it is up to the team to define.

The endpoint paths must follow the HTTP principles for everything.
