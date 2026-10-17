
-- 1. QUAIS PRODUTOS ESTAO CADASTRADOS
SELECT * FROM produtos;

-- 2. QUAIS PRODUTOS CUSTAM MENOS DE R$ 5,00
SELECT nome_pro, preco_pro
FROM produtos
WHERE preco_pro < 5.00;

-- 3. QUAIS PRODUTOS TEM MAIS DE 50 UNIDADES NO ESTOQUE
SELECT nome_pro, estoque_pro
FROM produtos
WHERE estoque_pro > 50;

-- 4. QUAIS CLIENTES SAO DE SAO PAULO
SELECT nome_cli, cidade_cli
FROM clientes
WHERE cidade_cli = 'são paulo';

-- 5. QUAIS SAO OS PRODUTOS MAIS CAROS
SELECT nome_pro, preco_pro
FROM produtos
ORDER BY preco_pro DESC;
