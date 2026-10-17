
# Projeto SQL - Sistema de Vendas

## Sobre o projeto

Este projeto foi desenvolvido com o objetivo de praticar os fundamentos de SQL por meio da criação de um banco de dados para um sistema de vendas.

O banco de dados permite organizar informações sobre clientes, produtos, vendas e itens vendidos, além de realizar consultas para obter informações úteis sobre os dados cadastrados.

## Tecnologias utilizadas

- SQL
- PostgreSQL
- Supabase

## Estrutura do banco de dados

O projeto possui quatro tabelas:

- **clientes:** armazena os dados dos clientes.
- **produtos:** armazena os nomes, categorias, preços e quantidades em estoque.
- **vendas:** registra as vendas realizadas e os clientes relacionados.
- **itens_de_venda:** registra os produtos, as quantidades e os preços de cada item vendido.

As tabelas são relacionadas por meio de chaves primárias (PRIMARY KEY) e chaves estrangeiras (FOREIGN KEY).

## Consultas SQL

Foram desenvolvidas consultas para:

- Listar os produtos cadastrados.
- Identificar produtos com preço inferior a R$ 5,00.
- Encontrar produtos com mais de 50 unidades em estoque.
- Consultar clientes de São Paulo.
- Ordenar produtos do maior para o menor preço.

## Organização dos arquivos

- `01_criacao_tabelas.sql`: criação das tabelas e relacionamentos.
- `02_insercao_dados.sql`: inserção dos dados iniciais.
- `03_consultas.sql`: consultas SQL para análise dos dados.

## Aprendizados

Com este projeto, estou desenvolvendo meus conhecimentos em criação de tabelas, relacionamentos entre dados, inserção de registros e consultas SQL utilizando SELECT, WHERE e ORDER BY.

Projeto desenvolvido para fins de estudo e construção de portfólio na área de Análise e Desenvolvimento de Sistemas.

