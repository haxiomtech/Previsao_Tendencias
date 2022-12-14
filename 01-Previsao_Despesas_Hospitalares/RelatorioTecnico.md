# Informações Técnicas do Projeto

#### Linguagem : R
#### Pacotes Utilizados: 

1. Estudo de correlação para encontrar as variáveis que mais implicam relacionamento com a coluna Gastos.
2. Montagem do algoritmo de regressão linear a fim de estudar o comportamento dos dados de entrada.
3. Aplicação do modelo na base nova de despesas-teste sem a coluna gastos.
4. Dados de saída: coluna de gastos preenchida conforme o perfil do novo cliente.

Para validar os novos dados de gastos gerados, obtivemos as seguintes informações:

![image](https://user-images.githubusercontent.com/119424591/207580220-ae405880-3476-441e-8c8a-cd5e2692f55c.png)

#### Resíduos
- Diferença entre os valores observados de uma variável e seus valores previstos.
Seus resíduos devem se parecer com uma distribuição normal, o que indica que a média entre os valores previstos e os valores observados é próximo de 0 (o que é bom).

#### Coeficiente - Intercept - a (alfa)
- Valor de a na equação de regressão f(x) = a + bx

#### Coeficientes - Nomes das variáveis - b (beta)
- Valor de b na equação de regressão

#### Erro Padrão
- Medida de variabilidade na estimativa do coeficiente a (alfa). O ideal é que este valor 
seja menor que o valor do coeficiente, mas nem sempre isso irá ocorrer.

#### Asteriscos 
- Os asteriscos representam os níveis de significância de acordo com o p-value.
Quanto mais estrelas, maior a significância.
Atenção --> Muitos astericos indicam que é improvável que não exista 
relacionamento entre as variáveis.

#### Valor t
- Define se coeficiente da variável é significativo ou não para o modelo. 
- Ele é usado para calcular o p-value e os níveis de significância.

#### p-value
- O p-value representa a probabilidade que a variável não seja relevante. 
- Deve ser o menor valor possível. 

#### Significância
- Espaço em branco - ruim
- Pontos - razoável
- Asteriscos - bom
- Muitos asteriscos - muito bom

#### Residual Standar Error
- Este valor representa o desvio padrão dos resíduos

#### Degrees of Freedom
- É a diferença entre o número de observações na amostra de treinamento  e o número de variáveis no seu modelo

#### R-squared (coeficiente de determinação - R^2)
- Ajuda a avaliar o nível de precisão do nosso modelo. 
- Quanto maior, melhor, sendo 1 o valor ideal.

#### F-statistics
- É o teste F do modelo. Esse teste obtém os parâmetros do nosso modelo e compara com um modelo que tenha menos parâmetros.
- Em teoria, um modelo com mais parâmetros tem um desempenho melhor. 


