# 🚀 Automação de CRM e Notificações Multicanais com n8n

## 📌 Visão Geral do Projeto
Este projeto consiste em um fluxo automatizado de integração e gestão de leads desenvolvido no **n8n**. A solução captura dados de um formulário público, armazena e organiza os registros em uma base de dados estruturada no **Google Sheets**, envia uma resposta transacional de confirmação ao cliente via **Gmail** e notifica instantaneamente a equipe de operações/vendas através do **Slack**.

O objetivo principal é demonstrar a construção de uma arquitetura *low-code* escalável, de baixo custo (100% gratuita) e com foco em eficiência operacional.

---

## 🛠️ Tecnologias e Ferramentas
- **n8n (Cloud/Local):** Orquestração do fluxo de trabalho e lógica de integração.
- **Google Forms:** Interface de entrada de dados (captura de leads).
- **Google Sheets:** Banco de dados relacional simplificado / CRM de persistência.
- **Gmail API (OAuth2):** Envio automatizado de e-mails de confirmação transacionais.
- **Slack (Incoming Webhooks / API):** Notificações e alertas em tempo real para comunicação interna.

---

## 📐 Arquitetura da Solução

## 📸 Evidências de Funcionamento

### Workflow no n8n
![Workflow do n8n](assets/n8n-workflow.png)

### Notificação no Slack
![Notificação no Slack](assets/slack-notification.png)

### E-mail de Confirmação
![E-mail no Gmail](assets/gmail-confirmation.png)
