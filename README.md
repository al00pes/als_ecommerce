 # Projeto de Análise de Dados de E-commerce 📊

Este projeto consiste na análise de dados de uma empresa de e-commerce que realiza a logística até o cliente final. 
Os dados foram tratados utilizando Jupyter Notebook com a linguagem Python, 
fazendo uso da biblioteca Pandas para o tratamento de dados em formato CSV e realizaçao a importação dos dados
no power BI para a construção de dashboard interativo.

## Objetivo 🎯

O objetivo deste projeto é realizar uma análise financeira dos pagamentos dos motoristas da empresa, mostrando os valores pagos por cidade e por galpão. Além disso, serão apresentados dados como ticket médio, valor total e quantidade de pacotes entregues por galpão. Também será mostrada a série histórica dos valores pagos aos motoristas por dia durante um período de 20 dias.

## Dataset

Os dados utilizados neste projeto são sintéticos e representam as operações financeiras da empresa de e-commerce. O dataset inclui informações sobre os pagamentos dos motoristas, as cidades de entrega e os galpões de distribuição.

## Ferramentas Utilizadas

- Jupyter Notebook
- Python
- Power BI

## Tratamento de Dados

O tratamento de dados foi realizado utilizando o Jupyter Notebook com Python e utilizando a biblioteca pandas. Foram realizadas as seguintes etapas de tratamento:

1. Leitura dos dados em formato CSV.
2. Modificação dos nomes da colunas
3. Modificando as palavras para maiúsculo.
4. Modificando os tipos dos atributos
5. Tratamento de missings.
6. exclusão de valores duplicados 
7. Join de diferentes arquivos CSV.
8. exclusão de colunas desnecessárias
9. Cálculo de métricas financeiras, como ticket médio e valor total.
   

## Criação do Dashboard no BI

Após o tratamento dos dados, foi gerado um arquivo CSV contendo os dados consolidados. Esse arquivo foi importado em uma ferramenta de Business Intelligence (BI) para a criação do dashboard. O dashboard apresenta as seguintes informações:

- Ticket médio por galpão.
- Valor total por galpão.
- Quantidade de pacotes entregues por galpão.
- Série histórica dos valores pagos aos motoristas por dia durante 20 dias.
- Porcentagem por tipo de veículo entregue

## Estrutura do Repositório

O repositório está estruturado da seguinte forma:

- `data/`: Contém os arquivos CSV com os dados brutos. ( Não foi possivel subir o arquivo)
- ` tratamento_dados/`: Contém o Jupyter Notebook utilizado para o tratamento dos dados.
- `output/`: Contém o arquivo CSV gerado após o tratamento dos dados. ( Não foi possivel subir o arquivo)
- `pacotes_financeiro.pbix/`: Contém os arquivos relacionados ao dashboard criado no BI.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues com sugestões e melhorias.

