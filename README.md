# Desafio de projeto - DIO - Python e Pandas  #
Repositório criado no Desafio de Projeto DIO - Análise de dados com Python e Pandas, no Bootcamp Geração Tech Unimed-BH - Ciências de Dados.
  
:file_folder: Datasets - Arquivos .xlxs base

:file_folder: Notebooks - Arquivos contendo códigos da exploração e imagens dos gáficos
  
## Sumário - Resultado da Análise Exploratória ##

- [**Questionamentos preliminares que podem ser feitos na Análise Exploratória**](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/README.md#insights-preliminares-obtidos-atrav%C3%A9s-da-an%C3%A1lise-explorat%C3%B3ria)
  - Qual a receita total de vendas?
  - Qual o custo total das vendas realizadas?
  - Qual o lucro bruto obtido das vendas?
  - Qual o tempo médio entre a venda e o envio do produto?
  - Qual o tempo médio entre a venda e o envio do produto por marca?
  - Qual o lucro de vendas por ano?
  - Qual o lucro de vendas por marca?
  - Qual o lucro de vendas por ano e marca?
  - Qual o total de produtos vendidos?
- **Apresentando informações preliminares de forma gráfica**
  - Gráfico total de produtos vendidos
  - Gráfico lucro por ano
  - Gráfico de Lucro x Mês
  - Gráfico de Lucro x Marca
  - Gráfico de Lucro x Classe
- **Análises estatísticas com base no tempo de envio**
  - Análises estatísticas
  - Gráfico de Boxplot
  - Histograma

## Insights preliminares obtidos através da Análise Exploratória ##

| Receita Total de Vendas | |
|--- |--- |
| Receita Total | 5.984.606,14 |

| Custo Total das Vendas Realizadas | |
|--- |--- |
| Custo Total | 2.486.783,05 |

| Lucro Bruto Obtido das Vendas | |
|--- |--- |
| Lucro Bruto | 3.497.823,09 |

| Tempo médio entre a venda e o envio do produto | |
|--- |--- |
| Tempo Médio | 8,54 dias|

Média de tempo de envio por marca:

| Marca | Tempo Médio de Envio (dias) |
|--- |---: |
| Adventure Works | 8,66 |
| Contoso | 8,47 |
| Fabrikam| 8,51 |

Lucro Bruto por Ano:

| Ano | Lucro Bruto |
|--- |---: |
| 2008 | 1.920.077,71 |
| 2009 | 1.577.745,38 |

Lucro Bruto por Marca:

| Marca | Lucro Bruto |
|--- |---: |
| Adventure Works | 712.036,24 |
| Contoso | 194.674,95 |
| Fabrikam | 2.591.111,90 |

Lucro Bruto por Ano e Marca:

| Ano | Marca | Lucro Bruto |
|--- |--- |---: |
| 2008 | Adventure Works | 306.641,16 |
| | Contoso | 56.416,00 |
| | Fabrikam | 1.557.020,55 |
| 2009 | Adventure Works | 405.395,08 |
| | Contoso | 138.258,95 |
| | Fabrikam | 1.034.091,35 |

Total de Produtos Vendidos:

| Produto | Qtd. Produtos Vendidos |
|--- |---: |
| Headphone Adapter for Contoso Phone E130 Silver | 25232 |
|	Headphone Adapter for Contoso Phone E130 White | 25008
| Adventure Works Laptop15.4W M1548 Black | 1089
| Fabrikam Trendsetter 2/3'' 17mm X100 Grey | 1087
| Adventure Works Laptop15.4W M1548 Red | 1047
| Fabrikam Trendsetter 2/3'' 17mm X100 Black | 926
| Fabrikam Trendsetter 1/3'' 8.5mm X200 Black | 884
| Fabrikam Trendsetter 1/3'' 8.5mm X200 Grey | 845
| Fabrikam Trendsetter 1/3'' 8.5mm X200 White | 789

## Apresentando informações de forma gráfica ##

- Gráfico total de produtos vendidos

![Gráfico total de produtos vendidos](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/Datasets/Grafico_total_de_produtos_vendidos.png?raw=true)

- Gráfico lucro por ano

![Gráfico lucro por ano](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/Datasets/Grafico_lucro_por_ano.png?raw=true)

- Gráfico de Lucro x Mês

![Gráfico de Lucro x Mês](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/Datasets/Grafico_de_Lucro_x_Mes.png?raw=true)

- Gráfico de Lucro x Marca

![Gráfico de Lucro x Marca](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/Datasets/Grafico_de_Lucro_x_Marca.png?raw=true)

- Gráfico de Lucro x Classe

![Gráfico de Lucro x Classe](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/Datasets/Grafico_de_Lucro_x_Classe.png?raw=true)

## Realizando análises estatísticas com base no tempo de envio ##

- Análises estatísticas

| Descrição | Detalhe | Dias |
|--- |--- |--- |
mean | média de dias entre venda e envio | 8.5 |
std | Desvio padrão | 3.1 |
min | menor tempo entre venda e envio | 4.0 |
max | maior tempo entre venda e envio | 20.0 |
25% | 1/4 das vendas enviadas em até | 6.0 |
50% | 1/2 das vendas enviadas em até | 9.0 |
75% | 3/4 das vendas enviadas em até | 11.0 |

- Gráfico de Boxplot

![Gráfico de Boxplot](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/Datasets/Grafico_de_Boxplot.png?raw=true)
	
- Histograma

![Histograma](https://github.com/pedrooliveirape/desafio_de_projeto_python_pandas_dio/blob/main/Datasets/Histograma.png?raw=true)
