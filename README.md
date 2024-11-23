<div align="center">
</div>

# Django-auth-api
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)
[![Python Version](https://img.shields.io/badge/Python-3.12-green)](https://www.python.org/downloads/)

## Table of Contents
- [Django-auth-api](#django-auth-api)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Structure](#structure)
  - [Screenshots](#screenshots)
  - [Developers](#developers)
---
## Description
Authentication API with Django Rest Framework and Simple JWT

It includes features such as user registration, custom user model login, password change, and password reset through email. The API uses Simple JWT for token authentication.

Key Features
Custom User registration
Custom user model login
Password change for authenticated users
Password reset through email
Simple JWT token authentication

---
## Structure
Endpoints (URLs) define the structure of the API and how end users access data from our application using the HTTP methods - GET, POST, PUT, DELETE. 


Endpoint |Method | Role | Purpose
-- | -- |-- |--
`/api/v1/register` | GET | Anyone | Register new user
`/api/v1/profile/{id}` | GET | Any role with valid token | View a user profile
`/api/v1/login`| POST | role with token | Login with correct credentials 
`/api/v1/reset-password/{id}` | PUT | role with account | Resetting password
`/api/v1/change-password/` | DELETE | role with valid token  | Changing the password
`/api/v1/send-reset-email` | GET | role with valid token | sends reset password email

## Screenshots

<details>
  <summary>Click to view screenshots</summary>

  ![screenshot_1](https://github.com/user-attachments/assets/9bb2f5f9-d456-4681-b5de-8d82a3ef97d8)

</details>

---
## Developers

- [Ngeno Victor](https://www.linkedin.com/in/engenovic/)

    Happy coding! 🚀
