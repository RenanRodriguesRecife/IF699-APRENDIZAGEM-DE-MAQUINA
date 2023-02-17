
# SOM - Mapas Auto-Organiz aveis de Kohonen (SOM)

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

Quatization Error

  mede a qualidade do mapa (não dá partição)
  
    (se todo mudo é igual ao protótipo então é zero)
    
    
Obs: Rede neural se colocar muito neurônio pode dar overfit com pouco neurônio pode tornar uma regra fraca.

===============================

