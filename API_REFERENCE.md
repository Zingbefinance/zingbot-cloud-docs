# 🚀 ZingBot Cloud API Reference

Version : v1.0.0

Base URL

/api/v1

---

## 🔐 Authentication

POST /auth/register

POST /auth/login

POST /auth/logout

GET /auth/me

POST /auth/refresh

---

## 👤 Users

GET /users/profile

PUT /users/profile

PUT /users/password

DELETE /users/account

---

## 🏢 Workspaces

POST /workspaces

GET /workspaces

GET /workspaces/{id}

PUT /workspaces/{id}

DELETE /workspaces/{id}

---

## ⚡ Automations

POST /automations

GET /automations

GET /automations/{id}

PUT /automations/{id}

DELETE /automations/{id}

---

## 🪙 Tokens

POST /tokens/connect

GET /tokens/status

GET /tokens/holders

GET /tokens/liquidity

GET /tokens/marketcap

---

## 👥 Community

POST /community/telegram

POST /community/x

POST /community/discord

GET /community/status

---

## 📊 Analytics

GET /analytics/dashboard

GET /analytics/health

GET /analytics/activity

GET /analytics/growth

---

## 🤖 AI

POST /ai/chat

POST /ai/announcement

POST /ai/analyze

---

## 💳 Billing

GET /billing/plan

POST /billing/upgrade

GET /billing/history

---

## 🤝 Affiliate

GET /affiliate/dashboard

GET /affiliate/referrals

GET /affiliate/earnings
