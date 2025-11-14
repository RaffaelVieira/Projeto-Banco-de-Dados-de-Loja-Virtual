# 🛒 Projeto de Banco de Dados para E-commerce
Este projeto implementa um banco de dados completo para uma loja virtual, incluindo modelagem, normalização (1FN, 2FN, 3FN) e scripts SQL completos (DDL + DML).

# 📋 Estrutura do Projeto

#### 📁 ecommerce-database/
#### /sql
   #### ├── 01_create_tables.sql
   #### ├── 02_inserts.sql
   #### ├── 03_selects.sql
   #### ├── 04_updates_deletes.sql
#### /modelagem
   #### ├── der_revisado.png
   #### ├── normalizacao_1fn_2fn_3fn.pdf
#### README.md

# 🗄️ Modelo do Banco de Dados
Tabelas Principais:
Clientes - Informações dos clientes

Produtos - Catálogo de produtos

Categorias - Categorias de produtos

Pedidos - Registro de pedidos

Itens_Pedido - Itens de cada pedido

Pagamentos - Informações de pagamento

# 🚀 Como Executar
Pré-requisitos:
MySQL Server 8.0+ ou PostgreSQL 12+

MySQL Workbench ou pgAdmin 4

Git (para versionamento)

Execute os scripts em ordem:

sql
-- 1. Criação do banco e tabelas
SOURCE create_database.sql;

-- 2. Inserção de dados
SOURCE insert_data.sql;

-- 3. Teste as consultas
SOURCE select_queries.sql;

-- 4. Execute operações de atualização
SOURCE update_delete_operations.sql;

# 📊 Funcionalidades
✅ Scripts Incluídos:
create_database.sql - Criação do banco e todas as tabelas

insert_data.sql - Dados de exemplo para teste

select_queries.sql - 5 consultas complexas com JOIN, WHERE, ORDER BY

update_delete_operations.sql - 5 UPDATEs e 5 DELETEs com condições

# 🔍 Exemplos de Consultas:
Produtos por categoria com estoque

Pedidos com informações do cliente

Itens mais vendidos

Clientes com maior valor em compras

Produtos com estoque baixo

# 🛠️ Tecnologias Utilizadas
SQL (DML - Data Manipulation Language)

MySQL/PostgreSQL

Git para versionamento

Workbench/pgAdmin para desenvolvimento

# 📈 Conceitos Aplicados
Modelagem relacional

Normalização de dados

Integridade referencial

Consultas complexas

Transações SQL

Otimização de performance


