
# Simulação de Dados de Vendas em um Posto de Combustível

Este é um projeto pessoal que simula os dados de vendas de um posto de combustível fictício no período entre 2020 e 2022. O trabalho foi dividido em 3 partes: criação dos dados, criação do banco de dados e construção do dashboard.

1ª Parte: Criação dos Dados
Os dados de vendas foram gerados usando Python. Foi criado um arquivo com 10.000 linhas, onde para cada uma delas, de forma aleatória, foi atribuído o tipo de combustível (gasolina, gasolina aditivada ou etanol), uma data e hora para a compra dentro do intervalo de 2020 a 2022 e o volume abastecido. O valor gasto em cada compra foi calculado com base no tipo de combustível e na quantidade abastecida. Esses dados gerados foram então transferidos para um arquivo CSV.

2ª Parte: Criação do Banco de Dados
O arquivo CSV gerado foi importado para um banco de dados SQL, especificamente o PostgreSQL, utilizando o pgAdmin. Foi criada uma única base de dados com uma tabela contendo 5 colunas, onde os tipos de dados foram definidos de acordo com o conteúdo do CSV.

3ª Parte: Construção do Dashboard
Para a construção do dashboard, optei pelo uso do Power BI. Nele, disponibilizei um resumo desses dados, incluindo a média de vendas em diferentes períodos, as vendas totais ao longo dos anos e uma comparação entre a quantidade vendida e o volume abastecido. É possível filtrar esses valores por tipo de combustível e por data. 
