# APIs

## Supabase

### Auth

- Login Google
- Login Email
- Logout

---

## Transactions

POST /transactions

GET /transactions

PUT /transactions/:id

DELETE /transactions/:id

---

## Dashboard

GET /dashboard

---

## Goals

POST /goals

GET /goals

PUT /goals/:id

DELETE /goals/:id

---

## Emergency Fund

GET /emergency

PUT /emergency

---

## Chat

POST /chat

Request

{
"message":"Gastei R$40 no mercado"
}

Response

{
"category":"Alimentação",
"value":40,
"type":"Despesa"
}

---

## AI

OpenAI API

Responsável por:

- interpretar mensagens;
- classificar despesas;
- responder dúvidas;
- recomendar economia.
