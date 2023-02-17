
Partição: Um objeto só pertence a um grupo

  Partição: Não exclusiva: Fuzzy - grau de pertensimento

Cobertura: Um exmplo pode está em um ou dois grupos (estrutura mais difícil de ter)

Existe várias abordagens mas todas elas ou produzem uma hierarquia ou uma partição

As estruturas tem vários viês

k-means é o mais usado pois é simples e rápido

Não dá para fazer busca exaustiva e passa a fazer algoritmo interativo.

A função objetivo não deixa a comparação tão aberrante comparado com a mediana

O protótipo depende da distância que você usa

K-means robusto-mediana

k-means classico - média

============================

Aprendizado não supervisionado agrupamento

Objetivo - obter grupos homogênio e bem separado

Pesquisar matriz de contigência

indice (só se compara valores de mesma base)

F-mesure (não supervisionado)

Quanto mais próximo de 1 mais semelhante é as duas partições

Xie and Ben - O que tiver o valor menor é mais homogênia e bem separado

Silhoeuette -

Quanto for usar indice evlerno você 


===========================

O K-Means é um algoritmo de clustering usado para identificar grupos (ou "clusters") semelhantes em um conjunto de dados. Aqui está uma visão geral do processo de funcionamento do K-Means:
 
1. Especificação do número de clusters (K): O primeiro passo é especificar o número de clusters que você deseja encontrar em seus dados. Este número é chamado de "K".

2. Inicialização dos centroides: Em seguida, os centroides são inicializados aleatoriamente. Os centroides são pontos representativos que representam cada cluster.

3. Atribuição de pontos aos clusters: Em seguida, cada ponto de dados é atribuído ao cluster cujo centroide está mais próximo.

4. Recalculando os centroides: Depois que todos os pontos foram atribuídos a um cluster, os novos centroides são calculados como a média dos pontos em cada cluster.

5. Repetição: Os passos 3 e 4 são repetidos até que os centroides não mudem mais ou até que se atinja um número máximo de iterações.

6. Resultado final: O resultado final são os K clusters formados com seus respectivos centroides e pontos de dados atribuídos.
