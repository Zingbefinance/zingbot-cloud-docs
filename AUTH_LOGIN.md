# 🔐 POST /api/v1/auth/login

## Description

Authentifier un utilisateur et retourner un jeton JWT.

---

## Request

POST /api/v1/auth/login

---

## Body

{
  "email": "example@email.com",
  "password": "********"
}

---

## Success Response

Status: 200 OK

{
  "success": true,
  "access_token": "jwt_token",
  "token_type": "Bearer",
  "expires_in": 3600
}

---

## Error Responses

400 Bad Request

- Missing email or password

401 Unauthorized

- Invalid credentials

500 Internal Server Error

- Unexpected server error

---

## Validation Rules

- Email required
- Password required

---

## Authentication

No authentication required.
