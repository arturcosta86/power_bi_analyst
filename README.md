### DESAFIO POWER BI 📊

Dashboards elaborados com foco em estudos na ferramenta Power BI, visando construir um portfólio com cenários reais do dia a dia:

- [Dashboard Relatório de Vendas](Prática_aulas/AULA-DADOS_POWERBI-SAMPLES.pbix)

### DASHBOARD RELATÓRIO DE VENDAS 

<p align="center">
    <imag width="470" src="Prática_aulas/Power BI - Animação - Imgur.gif">
</p>
    
Acesse o dashboard completo no POWER BI ONLINE [neste link](https://app.powerbi.com/groups/me/reports/c99ff8fc-d3d5-4293-a894-4db9b44c3198/fd3797faef51c0fc1357?language=pt-BR&experience=power-bi&ownerId=8647d4d1-04d0-4c1a-8a4f-bf49d3e82ad6&referrer=embed.appsource)

#### Estrutura da base de dados

**Arquivo em Excel que contém inicialmente as seguintes colunas:**

- Segmento
- País
- Produto
- Banda de Desconto
- Unidades Vendidas
- Preço de Fabricação
- Preço de Venda
- Vendas Brutas
- Descontos
- Vendas
- COGS (Custo dos Produtos Vendidos)
- Lucro
- Data
- Mês Número
- Mês 
- Ano

**Métodos Aplicados de Tratamento dos Dados:**

- Os dados foram extraídos da base disponibilizada pela ferramenta do Power BI em "experimentar um conjunto de dados exemplos".
- Foi utilizado o método ELT permitindo que área de negócio utilize os dados de acordo com sua demanda de relatórios.
- Foi utilizado o Editor do Power Query para tratamento dos dados.
- Nenhuma nova coluna foi criada a partir dos dados.
- A transformação de dados priorizou correção de dados quanto a remoção de linhas vazias, mudança do inglês para o português no títulos das colunas, transformação para números inteiros arredondando para menos na coluna 'Unidades Vendidas', transformação de minúscula para maiúscula na coluna 'País' e 'Mês'.
- Quantidade de dados **16 Colunas** e **700 linhas**.

**Relatório de Vendas em POWER BI:**

1ª Página 
- Soma de 'Vendas' por 'Produto' utilizando o gráfico de Pizza
- Média de 'Preço de Venda' por 'Produto' utilizando o gráfico de Área
- Soma de 'Vendas' por 'Ano', 'Mês' e 'Segmento' utilizando o gráfico de Coluna
- 'Ano', 'Mês' utilizando o gráfico de Segmentação.

2ª Página
- Soma de 'Vendas' utilizando o gráfico de Cartão
- Soma de 'Unidades Vendidas' utilizando o gráfico de Cartão
- Soma de 'Produto' por 'País' utilizando o gráfico de Pizza
- Soma de 'Produto' por 'Ano' e 'Mês' utilizando o gráfico de Coluna
- Soma de 'Vendas' por 'País' utilizando o gráfico de Coluna

3ª Página

- Soma de 'Lucro' por 'Segmento' utilizando o gráfico de Pizza
- Soma de 'Vendas' e Soma de 'Unidades Vendidas' por 'País' utilizando o gráfico de Mapa
- Soma de 'Lucro' por 'País' utilizando o gráfico de Mapa
