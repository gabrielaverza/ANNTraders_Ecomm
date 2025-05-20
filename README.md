## 🇧🇷 ANNTraders Ecomm – Projeto de Migração de Desenvolvedor Azure

Este repositório foi desenvolvido como parte do **curso hands-on da Microsoft com mentor: Azure Developer Migration Project**.

### 📌 Descrição

O projeto consiste em uma aplicação web desenvolvida hospedada na plataforma **Azure**. A aplicação se conecta a um **banco de dados** para realizar operações de **consulta, inclusão e exclusão de itens em tabelas**.

### 🚀 Tecnologias Utilizadas

* Python 3 / Django
* HTML5 / CSS3
* Bootstrap
* Azure Web App
* Azure SQL Database

### 🔧 Funcionalidades

* Interface web para gerenciamento de itens
* Operações CRUD no banco de dados
* Deploy completo na nuvem via Azure

### 🖥️ Como Rodar Localmente

```bash
# Criar ambiente virtual
python -m venv env

# Ativar o ambiente virtual (Windows)
.\env\Scripts\activate

# Instalar dependências
pip install -r requirements.txt

# Criar e aplicar migrações
python manage.py makemigrations
python manage.py migrate

# Iniciar o servidor local
python manage.py runserver
```

A aplicação estará disponível em: [http://localhost:8000](http://localhost:8000)
  
---

## 🇺🇸 ANNTraders Ecomm – Azure Developer Migration Project

This repository was created as part of the **Microsoft hands-on course with mentorship: Azure Developer Migration Project**.

### 📌 Description

The project is a web application hosted on **Azure**. It connects to a **database** to perform **read, create, and delete operations** on tables.

### 🚀 Technologies Used

* Python 3 / Django
* HTML5 / CSS3
* Bootstrap
* Azure Web App
* Azure SQL Database

### 🔧 Features

* Web interface for item management
* Full CRUD operations on the database
* Fully deployed on Azure

### 🖥️ How to Run Locally

```bash
# Create virtual environment
python -m venv env

# Activate the virtual environment (Windows)
.\env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Create and apply migrations
python manage.py makemigrations
python manage.py migrate

# Start the local server
python manage.py runserver
```

The application will be available at: [http://localhost:8000](http://localhost:8000)
