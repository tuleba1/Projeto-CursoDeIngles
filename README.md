# 🧠 InglesEdu

**InglesEdu** é um aplicativo desenvolvido em **Python | Django** com o objetivo de criar e gerenciar um curso de inglês online.
O projeto serve como base para o desenvolvimento de uma plataforma educacional moderna, modular e escalável, focada em ensino de idiomas.

---

## 🚀 Objetivo da Plataforma

O **InglesEdu** foi criado com o intuito de:

* Desenvolver um ambiente web para gerenciamento de cursos, aulas e alunos;
* Implementar recursos de **autenticação, CRUD e API REST**;

---

## 🏗️ Estrutura Inicial

O projeto será organizado da seguinte forma:
**Ainda com alterações a ser feitas**
```
InglesEdu/
├── manage.py
├── inglesedu/          # Configurações principais do Django
├── core/             # Aplicação principal do sistema
├── templates/          # Templates HTML do projeto
├── static/             # Arquivos estáticos (CSS, JS, imagens)
└── README.md
```

---

## 🧩 Tecnologias Utilizadas

* **Python 3.12+**
* **Django 5.x**
* **Django REST Framework** (para futuras APIs)

---

## ⚙️ Como Rodar o Projeto

### 1️⃣ Criar e ativar o ambiente virtual

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### 2️⃣ Instalar dependências

```bash
pip install -r requirements.txt
```

### 3️⃣ Rodar as migrações iniciais

```bash
python manage.py migrate
```

### 4️⃣ Executar o servidor

```bash
python manage.py runserver
```

Acesse em: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📘 Futuras Implementações

* Sistema de login e cadastro com autenticação de usuários;
* Dashboard administrativo para professores;
* Cadastro e acompanhamento de cursos e lições;
* Sistema de progresso e certificados;
* Interface responsiva e moderna.

---


## 📝 Licença

Este projeto é de uso exclusivo e educacional.
