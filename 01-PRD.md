# 💰 Finance Chat

> Um aplicativo de organização financeira pessoal baseado em IA Conversacional.

O **Finance Chat** permite que o usuário registre receitas, despesas, metas financeiras e acompanhe sua evolução apenas conversando com um Agente Financeiro.

O objetivo é tornar o controle financeiro simples, intuitivo e acessível para qualquer pessoa.

---

## 📖 Sobre o Projeto

Grande parte das pessoas abandona aplicativos financeiros porque exigem muito preenchimento manual, possuem interfaces complexas e pouco auxiliam na criação de hábitos financeiros.

O Finance Chat resolve esse problema utilizando **Inteligência Artificial Conversacional**, permitindo que o usuário registre movimentações utilizando linguagem natural.

Exemplos:

> Gastei R$ 52 no mercado.

> Recebi meu salário.

> Paguei R$ 120 de gasolina.

A IA interpreta automaticamente:

- 💰 Valor
- 📅 Data
- 📂 Categoria
- 📈 Receita ou Despesa
- 📝 Descrição

---

# 🚀 Funcionalidades

- ✅ Registro financeiro por conversa
- ✅ Classificação automática das despesas
- ✅ Dashboard financeiro
- ✅ Histórico de movimentações
- ✅ Metas financeiras
- ✅ Reserva de Emergência automática
- ✅ Recomendações inteligentes
- ✅ Funcionamento Offline
- ✅ Sincronização com Supabase
- ✅ Login com Google
- ✅ Login por E-mail

---

# 🛡 Reserva de Emergência

No primeiro acesso o aplicativo cria automaticamente uma meta chamada:

**Reserva de Emergência**

O Agente Financeiro incentiva o usuário a criar o hábito de poupar.

Exemplo:

> "Você economizou R$ 250 este mês. Deseja adicionar esse valor à sua Reserva de Emergência?"

---

# 🤖 Agente Financeiro

O agente conversa naturalmente com o usuário e poderá:

- Registrar receitas
- Registrar despesas
- Organizar categorias
- Criar metas
- Explicar conceitos financeiros
- Mostrar gastos excessivos
- Incentivar economia
- Acompanhar objetivos financeiros

---

# 📱 Fluxo do Aplicativo

```text
Splash Screen

↓

Boas-vindas

↓

Continuar sem conta
ou
Criar conta

↓

Reserva de Emergência

↓

Chat Financeiro

↓

Dashboard

↓

Uso diário
```

---

# 🖥️ Tecnologias

## Frontend

- React
- TypeScript
- Tailwind CSS

## Backend

- Supabase

## Banco de Dados

- PostgreSQL

## Autenticação

- Supabase Auth

## Inteligência Artificial

- OpenAI API

## Deploy

- Vercel

---

# 🏗 Arquitetura

```text
Usuário

↓

React + TypeScript

↓

Supabase Auth

↓

Supabase Database

↓

OpenAI API

↓

Agente Financeiro
```

---

# 📂 Estrutura do Projeto

```text
finance-chat/

├── public/
├── src/
│
├── components/
├── pages/
├── hooks/
├── services/
├── contexts/
├── layouts/
├── assets/
├── types/
├── utils/
│
├── App.tsx
├── main.tsx
│
├── package.json
└── README.md
```

---

# 🎯 Roadmap

## MVP

- [x] Registro financeiro via chat
- [x] Dashboard
- [x] Histórico
- [x] Metas
- [x] Reserva de Emergência
- [x] Sincronização com Supabase

## Versão 1.0

- [ ] OCR de notas fiscais
- [ ] Importação de extrato bancário
- [ ] Notificações Inteligentes
- [ ] Widgets

## Versão 2.0

- [ ] Controle financeiro familiar
- [ ] Metas compartilhadas
- [ ] Exportação PDF
- [ ] Exportação Excel

## Versão 3.0

- [ ] Integração Open Finance
- [ ] IA Preditiva
- [ ] Fluxo de Caixa Inteligente
- [ ] Assistente Financeiro Completo

---

# 🎨 Design

Interface planejada para:

- Minimalista
- Moderna
- Dark Mode
- Mobile First
- Responsiva
- Acessível

---

# 🔐 Segurança

- Autenticação via Supabase Auth
- Criptografia de credenciais
- Sincronização segura
- Persistência local para funcionamento offline

---

# 📈 Objetivos do MVP

Validar se usuários conseguem:

- Registrar movimentações apenas conversando.
- Criar hábito financeiro.
- Economizar mais.
- Compreender seus gastos.
- Utilizar o aplicativo diariamente.

---

# 📚 Metodologia

Este projeto está sendo desenvolvido utilizando a abordagem **Vibe Coding**, onde o desenvolvimento é conduzido por documentação (PRD), Inteligência Artificial e refinamentos iterativos.

---

# 👩‍💻 Desenvolvido por

**Kamila Ribeiro**

Engenheira de Controle e Automação

Especialista em Transformação Digital e Inteligência Artificial

Fundadora da **Innova AI Solutions**

---

# 📄 Licença

Este projeto está licenciado sob a licença MIT.
