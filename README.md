## Regresão Linear em Python

## Introdução

Este estudo implementa uma Regressão Linear Simples com o objetivo de analisar a relação entre 
anos de educação superior e o salário dos colaboradores. A regressão linear simples é uma técnica
estatística utilizada para entender a relação entre uma variável dependente (neste caso, o salário) 
e uma variável independente (anos de educação superior).

## Etapas da Análise
1. Importação de Bibliotecas
Utilizamos bibliotecas como pandas para manipulação dos dados, seaborn e matplotlib para visualização,
e statsmodels para cálculos estatísticos da regressão.

2. Carregamento dos Dados
Os dados foram carregados em um DataFrame com as seguintes colunas principais:
- Anos_Educ_Superior: Número de anos de educação superior dos colaboradores.
- Salario: Salário anual dos colaboradores.

3. Ajuste do Modelo de Regressão Linear
O modelo de regressão linear foi ajustado utilizando a função OLS da biblioteca statsmodels.

4. Visualização dos Resultados
Foi gerado um gráfico de dispersão com a linha de regressão ajustada para visualizar a relação entre as variáveis.

5. Interpretação dos Resultados
Com base nos resultados do modelo de regressão:

Intercepto ($\beta_0$): O salário médio de um colaborador sem educação superior é de R$4.301,80.
Coeficiente ($\beta_1$): Cada ano adicional de educação superior está associado a um aumento médio de R$526,73 no salário.

6. Conclusão
O modelo sugere uma relação linear positiva entre os anos de educação superior e o salário dos colaboradores.
A partir disso, podemos inferir que o nível educacional tem um impacto significativo sobre a remuneração, sendo cada
ano adicional de estudo capaz de aumentar o salário em uma quantidade substancial.
      
