# 🔐 POST /api/v1/auth/register

## Description

Créer un nouveau compte utilisateur.

---

## Request

POST /api/v1/auth/register

---

## Body

{
  "first_name": "Marcelin",
  "last_name": "Gogbe",
  "username": "zingfinance",
  "email": "example@email.com",
  "password": "********"
}

---

## Success Response

Status: 201 Created

{
  "success": true,
  "message": "Account created successfully.",
  "user_id": 1
}

---

## Error Responses

400 Bad Request

- Missing required fields

409 Conflict

- Email already exists

500 Internal Server Error

- Unexpected server error

---

## Validation Rules

- First name required
- Last name required
- Username required
- Email must be valid
- Password minimum 8 characters

---

## Authentication

No authentication required.
