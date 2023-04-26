## LangChain + ChatGPT para análise de dados

Este é um código que utiliza a biblioteca LangChain e a API ChatGPT da OpenAI para realizar análise de dados em um conjunto de dados.

## Requisitos

Para executar este código, você precisará dos seguintes requisitos:

Uma conta na plataforma OpenAI e uma chave de API
Um arquivo CSV com os dados que deseja analisar

Antes de executar o código, é necessário preencher a chave de API da OpenAI no arquivo .env. Após isso, basta executar o arquivo langchain_chatgpt.py para rodar o código.

## O código irá executar as seguintes tarefas com o dataset modelo adicionado 'perfumes.csv':

- Identificar a categoria de produto com maior receita, o valor da receita e o produto mais vendido da categoria
- Calcular a receita total de cada categoria e salvar em um arquivo Excel chamado "revenue_summary.xlsx" no computador
- Gerar um gráfico de barras com a receita em milhões por categoria das 8 maiores categorias
- Criar um novo arquivo Excel chamado "analise_perfumes.xlsx" e adicionar um separador chamado "revenue_by_year_month". Em seguida, ler o dataframe adicionado que contém informações de receita de produtos. No separador "revenue_by_year_month", agregar as colunas "Year", "Month of the year" e "Product Revenue" para cada "Month of The Year" (Mês do Ano). Por fim, salvar o arquivo Excel como "analise_perfumes.xlsx" no computador.
- Gerar um gráfico com a receita por ano-mês.

