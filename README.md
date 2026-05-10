# SQL Server — Análise de Dados com Banco Relacional

Projeto de estudo com foco em modelagem e consultas SQL em um banco de dados 
relacional simulando o ambiente de uma empresa.

## Objetivo
Praticar modelagem relacional e escrita de queries analíticas usando SQL Server,
respondendo perguntas de negócio reais a partir dos dados.

## Estrutura do banco
8 tabelas: Categoria, Cliente, Produto, Fornecedor, Funcionário,
Pedido, Detalhe_Pedido e Endereço — relacionadas por chaves primárias e estrangeiras.

## Diagrama do banco
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
 ![Diagrama do Banco](diagrama.jfif)

## Consultas desenvolvidas
- Soma de preços por pedido com filtro HAVING
- Produto com maior volume de vendas em um período (BETWEEN + GROUP BY)
- Cliente com maior gasto no mês (JOIN múltiplo + ORDER BY)
- País com maior gasto total (agregação + JOIN em 3 tabelas)

## Tecnologias
- SQL Server
- T-SQL (JOIN, GROUP BY, HAVING, BETWEEN, subconsultas)
