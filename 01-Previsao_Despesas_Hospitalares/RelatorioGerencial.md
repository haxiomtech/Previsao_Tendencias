
# Relatório Gerencial

### Problema de Negócio: Previsão de Despesas Hospitalares

#### Visão dos primeiro dados da planilha: despesas.csv

![image](https://user-images.githubusercontent.com/119424591/207480301-943ff0d9-f94f-4c74-a195-8c5e8fd92eca.png)

#### Verificação de Correlação Entre as Variáveis

![image](https://user-images.githubusercontent.com/119424591/207476723-507adbac-728d-4793-86a6-8aaab626658e.png)

Esta técnica foi utilizada para que possamos escolher quais variáveis tem maior relacionamento entre a variável de estudo.

Relacionamentos interessantes:

- A idade e o bmi (IMC) parecem ter uma correlação positiva fraca, o que significa que com o aumento da idade, a massa corporal tende a aumentar. 
- Há também uma correlação positiva moderada entre a idade e os gastos, além do número de filhos e os gastos. Estas associações implicam que, à media que idade, massa corporal e número de filhos aumenta, o custo esperado do seguro saúde sobe. 

#### Previsão de Despesas dos Novos Clientes: Aplicação do Modelo de Machine Learning

1. Para compreender os relacionamentos entre os dados e a váriável de estudo: Gastos, aplicamos um algoritmo de machine learning.
2. Após o algoritmo compreender matematicamente os relacionamento das variáveis, aplicamos como dados de entrada, as informações contidas na planilha: despesas-teste.csv (dados de novos clientes e sem a coluna gastos). Como resultado de saída, o algoritmo previu quais seriam os gastos relativos a estes novos clientes. 

### Solução:

![image](https://user-images.githubusercontent.com/119424591/207480571-36ca87c2-5d1c-4245-83f4-c17917485509.png)
![image](https://user-images.githubusercontent.com/119424591/207482703-fcc8a7cc-d1b1-40c5-a1f2-e7a82646b776.png)

C





