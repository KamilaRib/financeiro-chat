# Banco de Dados

## Tecnologia

Supabase

PostgreSQL

---

# users

| Campo | Tipo |
|--------|------|
| id | UUID |
| name | TEXT |
| email | TEXT |
| created_at | TIMESTAMP |

---

# transactions

| Campo | Tipo |
|--------|------|
| id | UUID |
| user_id | UUID |
| type | income / expense |
| amount | DECIMAL |
| category | TEXT |
| description | TEXT |
| transaction_date | DATE |
| created_at | TIMESTAMP |

---

# goals

| Campo | Tipo |
|--------|------|
| id | UUID |
| user_id | UUID |
| title | TEXT |
| target_amount | DECIMAL |
| current_amount | DECIMAL |
| due_date | DATE |
| created_at | TIMESTAMP |

---

# emergency_fund

| Campo | Tipo |
|--------|------|
| id | UUID |
| user_id | UUID |
| target_amount | DECIMAL |
| current_amount | DECIMAL |
| created_at | TIMESTAMP |

---

# ai_messages

Histórico do Agente Financeiro.

| Campo | Tipo |
|--------|------|
| id | UUID |
| user_id | UUID |
| role | user/assistant |
| message | TEXT |
| created_at | TIMESTAMP |
