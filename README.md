# Trabalhe Conosco – Formulário HTML + N8N

Este é um projeto de formulário simples em HTML e CSS puro, integrado com o **n8n** via **Form Trigger**, para captação de currículos de candidatos interessados em vagas da empresa.

## 📋 Funcionalidades

- Formulário responsivo em HTML/CSS
- Coleta de dados pessoais e profissionais
- Upload de **foto** e **documento**
- Integração direta com o **n8n Form Trigger**
- Envio automático por e-mail via **Gmail node** no n8n

## 🚀 Como funciona

1. O usuário preenche o formulário.
2. O formulário envia os dados para um **endpoint do n8n** (`Form Trigger`).
3. O n8n processa as informações e envia um e-mail com todos os dados e arquivos anexados.

## ✍️ Personalização

Você pode adaptar os campos do formulário diretamente no HTML e sincronizar os nomes dos campos no `Form Trigger` do n8n para que tudo funcione corretamente.

## 📸 Exemplo de campos enviados

- Nome completo
- E-mail
- Endereço
- Cargo e área de interesse
- Pretensão salarial
- Foto e documento (anexos)

---

