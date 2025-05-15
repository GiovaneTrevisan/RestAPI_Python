# REST API com Flask, Flask-RESTful e SQLAlchemy

Este projeto é uma API RESTful desenvolvida com **Flask** que permite gerenciar usuários (nome e e-mail) através de operações **CRUD**. A API utiliza **SQLAlchemy** como ORM e **SQLite** como banco de dados local.

## Tecnologias Utilizadas

- [Python 3.10+](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Flask-RESTful](https://flask-restful.readthedocs.io/)
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/)

## Funcionalidades

-  **POST /api/users/** – Cria um novo usuário
-  **GET /api/users/** – Lista todos os usuários
-  **GET /api/users/<id>** – Busca um usuário por ID
-  **PUT /api/users/<id>** – Atualiza os dados de um usuário
-  **DELETE /api/users/<id>** – Remove um usuário



