# 🌩️ CloudConnect – Dashboard de Gestão com Airtable  

O **CloudConnect** é um web app desenvolvido como parte da disciplina *Programação e Plataformas*.  
O objetivo do projeto é oferecer um **sistema simples de gestão**, onde usuários podem cadastrar e visualizar **clientes, produtos e serviços**, com **persistência em nuvem via Airtable** e interface intuitiva.  

---

## ✨ Funcionalidades  

- 📋 **CRUD Completo**: Criar, Listar, Atualizar e Excluir registros.  
- 🔗 **Integração com Airtable API** para persistência em nuvem.  
- 🔐 **Autenticação via Token (PAT)**, configurado de forma segura em *Secrets*.  
- 📊 **Dashboard Interativo** com visão geral e atividades recentes.  
- ⚡ **Atualização em tempo real** ao criar ou editar registros.  
- 💻 **Interface responsiva e amigável**, construída com HTML, CSS e JavaScript.  

---

## 🛠️ Tecnologias Utilizadas  

- **Frontend:** HTML5, CSS3, JavaScript (fetch API)  
- **Banco de Dados em Nuvem:** Airtable (Base + Tabelas)  
- **Ambiente de Desenvolvimento:** Replit / VS Code  
- **Segurança:** Replit Secrets (armazenamento seguro do token)  

---

## 📦 Estrutura de Pastas  

/CloudConnect
│── index.html # Estrutura principal da aplicação
│── styles.css # Estilização (layout e responsividade)
│── app.js # Lógica CRUD e integração com API
│── README.md # Documentação do projeto


## 🚀 Como Rodar o Projeto  

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/CloudConnect.git
   
Configure as variáveis de ambiente com seu Token do Airtable, Base ID e Table Name.

No Replit, adicione em Secrets:

AIRTABLE_TOKEN

AIRTABLE_BASE_ID

AIRTABLE_TABLE_NAME

Abra o arquivo index.html no navegador ou rode direto pelo Replit.
