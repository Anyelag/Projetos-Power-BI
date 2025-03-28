# Documentação do Dashboard de Análise de Vendas - Projeto de Teste - Analista de Dados

https://app.powerbi.com/view?r=eyJrIjoiODMyOWM1ZmEtYThlOC00MjE0LTlkNzYtZjM4ZjRhMjg4ZDIzIiwidCI6ImUyNzBkODk5LWNjN2YtNDQ5OS1iN2FhLTNmMmRjNWI2OGUyNCJ9 

## Visão geral
O objetivo principal foi criar um dashboard interativo utilizando o Power BI, com base em dados fornecidos pela empresa. O dashboard tem como foco fornecer insights sobre vendas, clientes, fornecedores, produtos e estoque.

O dashboard foi estruturado em quatro telas principais, cada uma com análises específicas para diferentes aspectos do negócio. A seguir, descrevo cada uma das telas e os principais KPIs analisados.
## Fontes de Dados

As fontes de dados utilizadas para este projeto foram:

Clientes: Informações sobre os clientes, como nome, endereço, telefone, e-mail e registros de compras.

- Vendas: Dados detalhados de cada venda, incluindo cliente, fornecedor, produto, quantidade e valor total.

- Estoque: Informações sobre os níveis de estoque de produtos.

- Produtos: Detalhes sobre os produtos, incluindo nome, categoria, fornecedor e valor.

- Fornecedores: Informações sobre os fornecedores, incluindo nome, CNPJ, endereço e dados de compra.

 ![image](https://github.com/user-attachments/assets/23fd7187-cb34-4d59-b1d1-871641fffe89)


## Estrutura do Dashboard
### Inicio
- **Valor total de vendas:** Mostra o valor total gerado por todas as vendas.
- **Quantidade total de pedidos:** Total de pedidos realizados.
- **Quantidade total de itens vendidos:** Número de itens vendidos durante o período.
- **Faturamento por mês (gráfico de linha):** Um gráfico de linha que mostra a evolução do faturamento ao longo dos meses.
- **Dados detalhados de vendas:** Apresenta uma tabela com informações sobre cada venda, incluindo cliente, fornecedor, categoria do produto, quantidade, e valor total de cada venda.

 ### Clientes
- **Top 5 clientes por faturamento:** Os cinco melhores clientes com base no valor de suas compras.
- **Análise de vendas por cliente:** Tabela contendo dados sobre cada cliente, incluindo número de pedidos, quantidade comprada, valor total gasto, e percentual do valor total gasto pelo cliente.
- **Dados de contato do cliente:** Exibe os dados de telefone, e-mail, endereço de cada cliente.

### Fornecedores
- **Top 5 fornecedores por faturamento:** Lista dos cinco fornecedores com maior faturamento gerado.
- **Análise de vendas por fornecedor:** Exibe dados sobre vendas de cada fornecedor, como número de pedidos, quantidade de itens vendidos, valor total de vendas, e percentual do faturamento total gerado pelo fornecedor.
- **Exibição hierárquica de fornecedores:** Através de uma hierarquia, é possível explorar os produtos de cada fornecedor.
- **Dados de contato do fornecedor:** Informações como telefone, e-mail, endereço.

### Produtos
- **Top 5 produtos por faturamento:** Exibe os cinco produtos mais vendidos, com base no valor total de vendas.
- **Análise de vendas por produto:** Apresenta os dados detalhados sobre cada produto, como número de pedidos, quantidade vendida, valor total gerado.
- **Informações sobre estoque de produtos:** Uma tabela com os detalhes de cada produto, incluindo quantidade disponível em estoque.
