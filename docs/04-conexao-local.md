# Conexão Local

## 1. Ferramentas recomendadas

- **Azure Data Studio** (leve e multiplataforma)
- **SQL Server Management Studio (SSMS)**

## 2. Recuperar string de conexão

- No painel do SQL Database, clique em **Mostrar cadeia de conexão**
- Copie a string conforme o tipo: ADO.NET, JDBC, ODBC ou PHP

## 3. Testar Conexão

- Abra sua ferramenta de gerenciamento
- Informe servidor, login e senha
- Execute uma query de teste:
```sql
SELECT name FROM sys.databases;
```
