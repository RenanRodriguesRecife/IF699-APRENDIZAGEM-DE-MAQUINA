
# SOM - Mapas Auto-Organizáveis de Kohonen (SOM)

SOM  ́e uma rede neural artificial (Kohonen, 1995) que realiza simultaneamente agrupamento evisualização

SOM usa aprendizagem n ̃ao supervisionada para mapear dados multidimensionals em um espaço de dimensão reduzida (usualmente 2) chamado de mapa

O mapa é uma representação discretizada em dimensão reduzida dos dados de entrada



==================================

### Funcionamento

- Protótipos mais semelhantes são associados à nós que estão próximos no reticulado

- Protótipos menos semelhantes serão posicionados mais longe no reticulado

- Cada objeto seleciona o protótipo mais "adequado" para ele

- Esse protótipo (e aqueles da sua vizinhança na rede) é modificado para melhorar a adequação com o objeto

- SOM preserva

  - A ordem espacial dos protótipos no mapa
  
  - As dissimilaridades entre os objetos

====================================

- Um mapa tem K neuronios organizados geralmente em um reticulado retangular ou hexagonal

- A rede SOM tem duas camadas

  - uma camada de entrada (que cont ́em os objetos)

  - uma camada de representa ̧c ̃ao (mapa neuronal) cuja topologia é definida pela distância entre os neuronios e a função de vizinhança

- A cada neuronio é associado um protótipo no mesmo espaço de descrição dos objetos

- Todo neurônio é completamente conectado à camada de entrada

<img src="fdsf">

- O peso da conexão de cada neurônio é protótipo associado à ele

- Uma rede de 2 camadas fornece uma representação simultânea do mapa e dos protótipos

- O treinamento do mapa pode ser incremental ou por lote.

========================================

### Treinamento

- Competição: para agrupar os dados: o neurônio vencedor leva tudo

- Adaptação: o neurônio vencedor se ajusta para representar melhor o padrão.

- Cooperação: Os vizinhos também são ajustados proporcionalmente a sua distância para o vencedor.

#### Treinamento Incremental

- Apresenta-se um vetor de entrada (aleatória ou sequencialmente) à rede

##### Competição

  - O BMU (best matching unit) é o neuronio cujo protótipo é o mais similar (ou o menos dissimilar) ao vetor de entrada.
  
  - se b é o BMU do vetor de entrada x 


======================================

Quatization Error

  mede a qualidade do mapa (não dá partição)
  
    (se todo mudo é igual ao protótipo então é zero)
    
    
Obs: Rede neural se colocar muito neurônio pode dar overfit com pouco neurônio pode tornar uma regra fraca.

===============================

