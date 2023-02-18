
# Regressão linear

Aprendisado Supervisionado

Regressão: Se trata de Relacionar uma variável resposta ou as variáveis respostas (se for um Vetor), com um conjuto de variáveis descritivas.

Na regressão linear é simplificado o problema. pois ele não vai tentar descobrir uma função qualquer, ele vai tentar descobrir uma função linear que relacione as variáveis.


Tem os exemplos: cada exemplo é descrito por um ou mais atributos (como é um apredizados supervisionado teve alguém que pré classificou esses exemplos - classificação, ou tem o valor da variável numérica se o problema é de regressão)

Exemplo: relacionar o preço do apartamento com a área dele:

<img src="">

Depois de aprendido o modelo você pode fazer a previsão de qual é o preço médio dele. Pela função linear gerada.

### Treinamento

Cada exemplo é descrito por um par: 

(X, Y)

<img src="">

notação:

i - é o número da ordem do exemplo:

primeiro exemplo x(1); segundo exemplo x(2), resposta do primeiro exemplo y(1)

### Como funciona o Aprendizado

Você tem um conjuto de treinamentos que tem vários exemplos com seus valores e suas variáveis respostas.

O objetivo é aprender a função linear:

Y = a + bX

Obs: Nesse caso como só temos um atributo (x) se trata de uma regressão linear univariável.

Obs: A regressão linear pode ser feita com várias variáis (multi-variables) 
ex: Área, Número de quartos, número de andares, idade da casa...

<img src="">

<img src="">

Obs: Por conveniencia de notação define x0 = 1

O modelo linear pode ser escrito em termos do produto interno: O vertor linha de (teta) trasposta com o vetor coluna de X

O aprendizado consistem em aprender o valor do Vetor (Teta)


### Treinamento

Existe várias formas de tentar fazer o aprendizado: 

Uma das formas é usar o modelo da maxima verossimilhança

<img src="">

O aprendizado é feito baseado em uma função de custo:

1 - A função de custo é definida como sendo a soma dos quadrados dos desvios

U(i) -> é o valor previsto pelo modelo

y(i) -> é o valor observado

A idéia é minimizar o valor médio da soma dos quadrados dos desvios.

==============================================

A regressão linear é um método estatístico utilizado para modelar a relação entre duas variáveis, uma variável independente (X) e uma variável dependente (Y), através de uma linha reta.

O objetivo da regressão linear é encontrar a equação dessa linha reta, que melhor representa a relação entre as duas variáveis. Essa equação é dada por:

Y = a + bX

Onde:

- Y é a variável dependente

- X é a variável independente

- a é o coeficiente angular da reta, que representa o valor da variável Y quando X é igual a zero.

- b é o coeficiente linear da reta, que representa a variação de Y para uma unidade de variação em X.

Existem vários métodos para encontrar os valores de a e b, mas um dos mais comuns é o método dos mínimos quadrados, que minimiza a soma dos quadrados dos desvios entre os valores observados de Y e os valores previstos pela equação da reta.

Para aplicar a regressão linear, é necessário ter um conjunto de dados que contenha os valores da variável independente e da variável dependente. O processo envolve os seguintes passos:

1. Coletar os dados e organizá-los em um conjunto de pares ordenados (X,Y).

2. Calcular a média e o desvio padrão das duas variáveis.

3. Calcular o coeficiente de correlação entre as duas variáveis, para avaliar se existe uma relação linear entre elas.

4. Calcular os valores de a e b, usando o método dos mínimos quadrados.

5. Avaliar a qualidade da regressão, usando medidas como o coeficiente de determinação (R²) e o erro padrão da estimativa.
