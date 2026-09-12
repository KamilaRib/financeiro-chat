# 💰 Innova Finance

> Organize suas finanças de forma simples e inteligente através de Inteligência Artificial Conversacional.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-blue)
![Versão](https://img.shields.io/badge/version-0.1.0-orange)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-2-3ECF8E?logo=supabase&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?logo=google&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

Aplicativo de organização financeira pessoal desenvolvido durante o desafio da DIO utilizando **Vibe Coding**, **Claude Code**, **GitHub Copilot**, **Google Gemini** e **React**.

# 🚀 Objetivo do Projeto

Este projeto foi desenvolvido durante o desafio da DIO com foco em **Vibe Coding**, utilizando IA como apoio ao processo de desenvolvimento.

O objetivo é permitir que qualquer pessoa registre receitas, despesas, metas financeiras e acompanhe sua reserva de emergência através de linguagem natural, proporcionando uma experiência simples, intuitiva e inteligente.


# 💡 Conceito do Aplicativo

O **Finance Chat** é um aplicativo que permite ao usuário registrar movimentações financeiras através de uma conversa.

Exemplos:

> "Gastei R$ 50 no mercado."

> "Recebi meu salário."

> "Paguei R$ 120 de gasolina."

A Inteligência Artificial interpreta automaticamente:

- 💰 Valor
- 📅 Data
- 📂 Categoria
- 📈 Receita ou Despesa
- 📝 Descrição

O sistema também oferece:

- Dashboard financeiro
- Histórico de movimentações
- Metas financeiras
- Reserva de emergência
- Recomendações inteligentes
- Funcionamento Offline (PWA)
- Sincronização com Supabase

---

# 🧠 Prompt Final (PRD)

## 📋 Estruturação do **PRD (Product Requirements Document)** como contexto principal para orientar a IA.

O desenvolvimento do **Innova Finance** iniciou pela criação de um **PRD (Product Requirements Document)**, utilizado como documento central para orientar todas as decisões de produto e desenvolvimento.

Durante essa etapa foram definidos:

- 🎯 Objetivo do projeto
- 👥 Público-alvo e personas
- ❗ Problema que o aplicativo resolve
- 📱 Jornada e fluxo do usuário
- ⚙️ Funcionalidades do MVP
- 📐 Regras de negócio
- 🗄️ Modelagem inicial do banco de dados
- 🔌 Estrutura das APIs
- 🤖 Comportamento da Inteligência Artificial
- 🏗️ Arquitetura técnica da aplicação
- 📅 Roadmap do produto
- ✅ Backlog de tarefas para implementação

Essa documentação serviu como base para orientar o **Claude Code**, **Antigravity IDE** e outras ferramentas de IA durante o desenvolvimento, reduzindo ambiguidades e permitindo gerar código de forma mais consistente.

**Documentação completa:**

```text
docs/01-PRD.md
```

### 📸 Estruturação do PRD

> Adicione abaixo uma captura de tela do processo de criação do PRD.

![Criação do PRD](docs/images/prd.png)

O PRD define:

- Objetivos do projeto
- Público-alvo
- Funcionalidades
- Fluxos do usuário
- Regras de negócio
- Arquitetura técnica
- Banco de dados
- APIs
- Roadmap
- Backlog de desenvolvimento

O documento completo encontra-se em:

```text
docs/01-PRD.md
```

---

# 🤖 Ferramentas de IA Utilizadas

Durante o projeto utilizei diferentes ferramentas para estruturar e validar o desenvolvimento:

- ChatGPT
- Claude Code
- Antigravity IDE
- GitHub Copilot
- Google Gemini (planejado como provedor de IA da aplicação)

---

# 📂 Documentação

```text
docs/
├── 01-PRD.md
├── 02-SYSTEM-DESIGN.md
├── 03-DATABASE.md
├── 04-API.md
├── 05-PROMPTS.md
├── 06-ROADMAP.md
├── 07-TECHNICAL-ARCHITECTURE.md
└── 08-TASKS.md
```

---

# 📸 Processo de Desenvolvimento

## Estruturação do PRD

> Adicione aqui uma captura de tela do PRD sendo criado.

```
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/88d55fcb-3807-464d-8ab3-4a6879507f4d" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a52e3aaa-792a-4444-8a89-f5dfcb491fb6" />


```

---

## Interação com a IA

> Adicione aqui imagens do ChatGPT, Claude Code, GitHub Copilot ou Lovable sendo utilizados durante o desenvolvimento.

Exemplo:

```

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5bf481f6-1c08-46d1-8fff-08b74ef1bd48" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6a0ebfe2-6a74-4348-9ca0-1257bc3b2c2f" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fb3571dd-cbf3-4061-9b64-bd7c3f953736" />

```

---

## Arquitetura do Sistema

> Adicione aqui um diagrama da arquitetura.

```
docs/images/architecture.png
```

---

### Melhorias realizadas com IA

Durante o desenvolvimento, utilizei o Claude Code para revisar a interface inicial.

A partir dessa interação, foi sugerida e implementada uma **Bottom Navigation Bar**, melhorando significativamente a experiência do usuário em dispositivos móveis.

A navegação passou a contar com acesso direto às principais funcionalidades do aplicativo:

- Dashboard
- Chat
- Histórico
- Metas
- Perfil

Essa abordagem demonstrou como ferramentas de IA podem auxiliar não apenas na implementação, mas também na evolução da experiência do usuário.

feat(ui): adiciona barra de navegação inferior para melhorar a experiência mobile
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b2ffcc61-4b4f-46f9-bb42-f00873ec25aa" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48d7ae5c-07bc-4268-b73a-95ad1315e194" />


# 📚 Tecnologias

- React
- TypeScript
- Tailwind CSS
- Supabase
- PostgreSQL
- Google Gemini
- Vercel

---

# 🎯 Aprendizados

Durante este projeto aprendi que desenvolver aplicações utilizando Inteligência Artificial vai muito além de pedir para a IA escrever código.

Os principais aprendizados foram:

- Como estruturar um PRD para orientar ferramentas de IA.
- A importância de definir arquitetura antes da implementação.
- Como documentar requisitos funcionais e técnicos.
- Como dividir um projeto em pequenas tarefas para facilitar o desenvolvimento assistido por IA.
- Como utilizar ferramentas como ChatGPT, Claude Code e Antigravity IDE de forma complementar.
- A importância de criar uma documentação consistente para melhorar a qualidade do código gerado.

Este projeto demonstrou que a combinação entre documentação bem estruturada e ferramentas de IA permite acelerar o desenvolvimento sem abrir mão da organização e da qualidade técnica.

---

# 👩‍💻 Desenvolvido por

**Kamila Ribeiro**

Engenheira de Controle e Automação

Especialista em Transformação Digital e Inteligência Artificial
