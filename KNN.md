# K Nearest Neighboors (KNN)
## Objetívo:
Determinar o rótulo de classificação de uma amostra baseado nas amostras vizinhas de um conjunto de treinamento.

## Características:
* Método baseado em calculo de distância
* Poder ser utilizado para classificação quanto para regressão.

## Conceitos
* Hipótese é que dados semelhantes tendem a estar concentrados no mesmo espaço de dispersão.
* Considera a proximidade dos dados para realizar as predições.
* Pode trabalhar com diferentes medidas de distância (Euclidiana).
* O parâmetro K especifica quantos vizinhos serão separados.
* Quanto maior o valor de K, maior será o número de amostras a serem comparadas.

## Parâmetros e otimização:
* A escolha do parâmetro K é de vital importância para o melhor resultado do modelo.
* O algoritmo se beneficia da possibilidade de utilização de diferentes métricas de distância (Euclidiana,Manhattan,Minkowski e etc...)

## Pseudocódigo do funcionamento:
#### Inicialização:
* Prepara conjunto de dados de entreda e saída
* Informar o valor de K.
#### Para cada nova amostra Faça:
* Calcular distância para todas as amostras.
* Determinar o conjunto das K's distâncias mais próximas.
* O rótulo com mais respresentantes no conjunto dos K's vizinhos será o escolhido.
#### Fim para :
* Retornar: Conjunto de rótulos de classificação
