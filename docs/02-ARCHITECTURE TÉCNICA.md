# Arquitetura Técnica

## Stack

Frontend

- React
- TypeScript
- Tailwind

Backend

- Supabase
- Edge Functions

Banco

- PostgreSQL

IA

- OpenAI

Deploy

- Vercel

---

## Fluxo

Usuário

↓

React

↓

Supabase Auth

↓

Supabase Database

↓

Edge Functions

↓

OpenAI

↓

Dashboard

---

## Fluxo de Login

Usuário

↓

Google Login

↓

Supabase Auth

↓

JWT

↓

Dashboard

---

## Fluxo Financeiro

Usuário

↓

Chat

↓

OpenAI interpreta

↓

Supabase grava

↓

Dashboard atualiza
