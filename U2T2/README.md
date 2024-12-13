# Avaliação de Algoritmos com BST
Este repositório contém um notebook que avalia o desempenho de algoritmos 
utilizando uma Árvore de Busca Binária (BST) como estrutura de dados.

## Pré-requisitos
- Python 3.8+
- Bibliotecas: `numpy`, `matplotlib`, `pytest`, `plotly`

# Solver Kth Largest
## Implementação de classes
 Temos presente na primeira parte deste trabalho a implementação de Node e BST.
uma arvore binaria gerada como exemplo usado no notebook.

<img src="https://github.com/user-attachments/assets/e69c5bca-5709-4f2c-b428-099405ca510a" alt="BST">

## Geração de dados 
 É uma função presente no notebook deste trabalho para gerar dados testes aleatorios
 e seus diferentes tamanhos de entradas para uso do algoritmo.

## Medição de Desempenho 
 Utiliza uma cédula com a importação do módulo time, para ser calculado o tempo médio e inervalo de confiança de sua execução 
 e dos dados gerados anteriormente.

## Grafico
 Apresenta um grafico gerado pelo dados aleatorios estabelecidos e seu intervalo de confiança, estabelecendo o gráfico com seu tempo de execução.
 
 <img src="https://github.com/user-attachments/assets/6a8aa6df-f4e8-4738-9596-3bf289fbed29" alt="">

## Solver Closest
 O objetivo deste algoritmo é encontrar o valor mais próximop de um numero-alvo dentro de um BTS
 
### Neste algoritimo temos semelhança com o codigo anterior tendo implementado as seguintes cedulas.
- Geração de Dados : Cria árvores de busca binária (BST) balanceadas com tamanhos variados para os testes.
- Avaliação de desempenho: Medimos o tempo médio e intervalo de confiança para o algoritmo findClosestValue nas árvores geradas
- Comparação com listas: Compara o desempenho do algoritmo usando listas ordenadas como estrutura de dados
- Gráfico
  
   <img src="https://github.com/user-attachments/assets/8937b579-3a3f-4adb-b4d4-bc3d6ba6acab" alt="">
