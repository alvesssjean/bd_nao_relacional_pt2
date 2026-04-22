# Arquivos
- docker-compose.yml
- database.py
- models.py
- schemas.py
- main.py
- env

# Docker Compose
Sobe o PostgreSQL localmente sem instalar nada na máquina.

# Conxeão com SQL Alchemy
Criar, engine,, sessão e base declarativa para os modelos.

# Modelos ORM
Classes Python mapeadas para tabelas do banco de dados.

# Migrations com Alembic
Controle de versão do schema do banco, sem perder dados.

# Rotas CRUD com FastAPI
Endpoints que leem e escrevem no banco de dados usando a sessão do SQL Alchemy.


# Para rodar: criar arquivo .env com "DATABASE_URL=postgresql://usuario:senha123@localhost:5433/meubanco"