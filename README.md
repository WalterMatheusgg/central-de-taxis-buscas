<div align="center">

# 🚖 Taxi Service — Busca e Testes
### Aplicação Django para estudos de desenvolvimento web

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Tests](https://img.shields.io/badge/Testes-Django-475569?style=for-the-badge)

</div>

## 🎯 Visão geral

Projeto de aprendizado Django com **modelos de motoristas, carros e fabricantes**, páginas para consulta e busca e foco na prática de testes automatizados e controle de acesso.

Este repositório faz parte de uma sequência de exercícios de Django; deve ser apresentado como **projeto educacional**, e não como plataforma de transporte em operação.

## ✨ Funcionalidades descritas

| Recurso | Escopo |
|---|---|
| 🚗 Veículos | Cadastro e consulta de automóveis |
| 🏭 Fabricantes | Relação entre veículos e fabricantes |
| 🧑‍✈️ Motoristas | Registro e consulta de condutores |
| 🔎 Busca | Pesquisa em listagens de entidades |
| 🔐 Acesso | Páginas com proteção por autenticação |
| 🧪 Testes | Exercícios de teste de modelos, views e buscas |

## 🏗️ Estrutura

```text
taxi/             # Models, views, forms, urls e migrations
taxi_service/     # Configurações e rotas Django
templates/        # Templates HTML
static/           # Assets estáticos
manage.py         # Comandos Django
requirements.txt  # Dependências
```

## 🚀 Execução local

```bash
git clone https://github.com/WalterMatheusgg/py-taxi-service-search-and-tests.git
cd py-taxi-service-search-and-tests
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py test
python manage.py runserver
```

Acesse `http://127.0.0.1:8000/`. O repositório pode necessitar de dados iniciais para algumas páginas.

**Segurança:** não reutilize credenciais de exemplo em ambientes públicos. O projeto é destinado a **desenvolvimento e aprendizado**, sem validação de produção.

## 🧠 Competências abordadas

Django ORM, models, class-based views, Django Templates, formulários, filtros por querystring, autenticação e testes.

## 👨‍💻 Autor

**Walter Matheus Soares da Silva** · [GitHub](https://github.com/WalterMatheusgg)
