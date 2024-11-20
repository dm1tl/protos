# Protos Repository

### Project Description

This repository contains the Protocol Buffers (`.proto`) definition and the generated Go code for the Authorization Service. The .proto file defines gRPC services and messages for user authentication, authorization, and account management.  

It serves as a shared resource for generating gRPC client and server code in various programming languages, enabling seamless integration between services.

---

### Features

#### Auth Service
- Register: Register a new user.  
  RPC: Register(RegisterRequest) returns (RegisterResponse)  

- Login: Authenticate a user and issue a token.  
  RPC: Login(LoginRequest) returns (LoginResponse)  

- ValidateToken: Validate a JWT token to ensure its authenticity and validity.  
  RPC: ValidateToken(ValidateTokenRequest) returns (ValidateTokenResponse)  

#### User Service
- Delete: Delete a user account.  
  RPC: Delete(DeleteRequest) returns (DeleteResponse)  
