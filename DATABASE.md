# 🗄️ ZingBot Cloud Database

## Database

PostgreSQL

---

# Main Tables

## Users

- id
- first_name
- last_name
- username
- email
- password_hash
- avatar
- role
- plan
- is_verified
- created_at

---

## Workspaces

- id
- owner_id
- name
- slug
- description
- project_type
- blockchain
- status
- created_at

---

## Automations

- id
- workspace_id
- type
- status
- configuration
- created_at

---

## Tokens

- id
- workspace_id
- mint_address
- symbol
- blockchain
- liquidity
- holders
- marketcap

---

## Communities

- id
- workspace_id
- telegram_channel
- telegram_group
- x_account
- discord_server

---

## Subscriptions

- id
- workspace_id
- plan
- status
- renewal_date

---

## Affiliate

- id
- user_id
- referral_code
- earnings
- referrals
