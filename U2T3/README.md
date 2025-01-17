# Trabalho sobre algoritmos do Dijkstra e Kruskal
## Primeira parte sobre o uso e comparação do algoritimo de dijkstra e networkx com o osmnx
- Neste trabalho foram escolhidos 10 pares de destino da cidade de Natal-RN, entre os pontos selecionas esta os shoppings da capital, hospital e locais de lazer.
- Abaixo vai estar presente grafos que mostra a interligação entres os pontos selecionados. Feito pelo algoritimo dijkstra com Min heap e OSMNx.

  -Midway para Natal Shopping

   <img src="https://github.com/user-attachments/assets/5887e6aa-b0a6-46ef-a889-f2c2c3282130" alt="BST">

  -Natal shopping para Praia Shopping

   <img src="https://github.com/user-attachments/assets/0fbbc555-43fc-4063-a5be-d897710de16b" alt="BST">

  -Midway para Arena das Dunas

   <img src="https://github.com/user-attachments/assets/472cd7e6-b40b-4b32-8aac-56089e085942" alt="BST">

  -Arena para Parque

   <img src="https://github.com/user-attachments/assets/40c548e6-b198-43ed-855d-d3fa5a86ba3e" alt="BST">

   -UFRN para Parque

   <img src="https://github.com/user-attachments/assets/215b8664-243d-4fcc-85f7-c6af1fe4c243" alt="BST">
   
   - UFRN para Midway

   <img src="https://github.com/user-attachments/assets/8c06492f-9a61-4c40-8c2b-c44275de2bd1" alt="BST">

   - Praia Shopping para UFRN

   <img src="https://github.com/user-attachments/assets/69a89a30-bcb8-4b1f-957f-0e33281ee947" alt="BST">

   - Leroy Merlim para Facex

   <img src="https://github.com/user-attachments/assets/fc94fd70-c940-4c22-aa63-b2a84f0a0b79" alt="BST">

   - hospital do Coração para Arena das Dunas

   <img src="https://github.com/user-attachments/assets/041bcd3b-95f9-4652-82e1-f130f4135998" alt="BST">

   - Arena das Dunas para Praia Shopping

   <img src="https://github.com/user-attachments/assets/2afa7b28-e389-43a3-8a9b-08223bb76b5e" alt="BST">

## O principal objetivo deste trabalho além de elaborar os grafos, é abordar a comparação entre o modelo do dijstra e networkx.  
E isso foi elaborado no marquivo notebook obtendo os seguintes resultados.

  <img src="https://github.com/user-attachments/assets/a1541bd4-167a-4227-aff7-2967d5d18a7b" alt="BST">

  Com base nestes resultado, podemos concluir que as distâncias calculadas pela implementação manual do algoritmo de Dijkstra são iguais às do NetworkX para todos os nós acessíveis (nós de 0 a 5). Para os nós inalcançáveis (nós 6, 7 e 8), ambas as abordagens retornaram inf corretamente.  
  Os caminhos reconstruídos pela implementação manual também são iguais aos do NetworkX para os nós acessíveis.   
  Apresentando um  Tempo de execução:  
Manual: 0.000557 segundos  
NetworkX: 0.002133 segundos  

  Por final temos as distancias entres os 10 detinos em Km.  

  <img src="https://github.com/user-attachments/assets/18b6e265-9311-45ab-ba05-c33208813da9" alt="BST">  

## Segunda parte, implementação do algoritmo Kruskal para pontos turisticos de Ntal/RN  
Foi usado para construir a Árvore Geradora Mínima (MST), conectando todos os pontos turísticos com o menor custo.  
Isso é útil em situações práticas como a construção de infraestrutura viária eficiente ou roteiros turísticos econômicos.  
O trabalho demonstra como usar algoritmos para planejar roteiros turísticos eficientes, minimizando deslocamentos.  
Isso é especialmente útil para empresas de turismo ou para a prefeitura ao organizar mapas turísticos otimizados.  

<img src="https://github.com/user-attachments/assets/684f10e4-f296-44f0-ada3-ce6aa0709099" alt="BST">  

Em conclusão, este trabalho demonstra a força dos algoritmos em grafos na solução de problemas reais, como o planejamento de rotas e infraestrutura. Através de ferramentas como OSMnx e NetworkX, foi possível modelar e resolver problemas urbanos complexos, gerando insights úteis para planejamento urbano, turismo e transporte. O modelo é escalável e pode ser aplicado em outros contextos e localidades.  

link de videos no Loom: 
- dijsktra https://www.loom.com/share/77507bc5d85542e99ae210ad340b810d
- kruskal https://www.loom.com/share/8871f82aad884d5d90d863852c4d554c

