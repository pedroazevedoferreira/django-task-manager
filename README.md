# Sistema de Tarefas (Django + SQLite)

CRUD de tarefas com autenticação de usuários.

## Como rodar (local)

1. Python 3.10+ recomendado.
2. Criar e ativar virtualenv:
   - Windows: `python -m venv venv` & `venv\Scripts\activate`
   - Mac/Linux: `python -m venv venv` & `source venv/bin/activate`
3. Instalar dependências:
```bash
pip install -r requirements.txt
```
4. Rodar migrações:
```bash
python manage.py migrate
```
5. Criar usuário padrão (opcional — já incluí um script para criar):
```bash
python create_default_user.py
```
Usuário: `admin`
Senha: `1234`

6. Rodar servidor:
```bash
python manage.py runserver
```

Acesse http://127.0.0.1:8000/ e faça login.

