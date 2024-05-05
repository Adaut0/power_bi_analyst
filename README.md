# power_bi_analyst
Repositório do desafio DIO Power BI

# Diferença na Utilização dos Comandos Mesclar, Atribuir e Combinar no Power BI

No Power BI, os comandos "mesclar", "atribuir" e "combinar" são utilizados para manipular e relacionar conjuntos de dados de diferentes maneiras. Vou explicar cada um deles e quando seria melhor utilizar o comando "mesclar".

## Mesclar (Merge)

O comando de mesclagem é usado para combinar duas tabelas ou consultas com base em uma ou mais colunas comuns. Ele cria uma nova tabela que contém todas as colunas das tabelas originais, combinadas com base nos valores correspondentes nas colunas de mesclagem. Por exemplo, você pode mesclar uma tabela de vendas com uma tabela de clientes com base no ID do cliente, para vincular as informações de vendas às informações do cliente.

## Atribuir (Append)

O comando de atribuição é usado para concatenar duas tabelas ou consultas, uma abaixo da outra, criando uma tabela maior. Por exemplo, se você tiver duas tabelas de vendas para diferentes anos e quiser combiná-las em uma única tabela para análise histórica, poderia usar o comando de atribuição.

## Combinar (Combine)

O comando de combinação é usado para unir duas ou mais tabelas ou consultas que têm a mesma estrutura, combinando linhas com base em suas posições nas tabelas originais. Por exemplo, se você tiver várias fontes de dados que possuem a mesma estrutura (por exemplo, diferentes arquivos CSV com as mesmas colunas) e deseja combiná-las em uma única tabela, poderia usar o comando de combinação.

Na situação do desafio, a melhor escolha seria utilizar o comando de mesclar, pois nele você precisa combinar informações de diferentes tabelas com base em colunas comuns, como IDs de cliente, nomes de produtos, datas, etc. Neste exemplo, se você estiver construindo um relatório que precisa mostrar informações de departments junto com informações de employee, a mesclagem é a escolha adequada para relacionar esses conjuntos de dados com base em um identificador comum.
