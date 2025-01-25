# Trabalho Final  
## Dados e geração de graficos de portais de noticias e dados sobre final da copa do mundo de 2022  
### Este projeto utiliza técnicas de análise de dados e visualização de redes para explorar as interações e dinâmicas da final da Copa do Mundo de 2022 entre Argentina e França.  

  # Descrição do Projeto  
   O objetivo do trabalho é analisar o impacto de jogadores-chave, como Lionel Messi e Mbappé, e as relações entre os jogadores durante o jogo. O projeto aplica diferentes ferramentas e métricas para revelar padrões e insights que destacam as estratégias e o desempenho em campo.  
  
  # Principais funcionalidades
1 - Análise de Redes (Graph Theory):  
Construção de grafos com base nas interações (gols, assistências, passes decisivos).  
Cálculo de métricas de centralidade (grau, PageRank).  
Detecção de comunidades (algoritmo de Louvain).  
  
2 - Análise de Textos:  
Extração de entidades nomeadas (NER) usando o SpaCy.  
Frequência de palavras e remoção de stopwords com o NLTK.  
Análise de sentimentos e complexidade textual.   
  
3 - Visualização de Dados:

Geração de grafos interativos para visualização no Gephi.  
Visualização estática dos grafos usando o NetworkX e Matplotlib.

  ### Bibliotecas  
  As bibliotecas necessárias para executar o notebook são:

Python (3.7)
Bibliotecas Python:  
                spacy  
                nltk  
                networkx   
                matplotlib  
                pandas  

# Estrutura do Notebook
### 1. Configuração Inicial  
Instalação e importação de bibliotecas.  
Download dos modelos necessários para SpaCy e NLTK.  
### 2. Extração de Entidades  
Processamento dos textos das notícias sobre a final da Copa do Mundo.  
Criação de grafos com base nas entidades detectadas.  
### 3. Construção de Grafos  
Dados numéricos fornecidos (gols, assistências e passes decisivos).  
Exportação para o formato .gml para uso no Gephi.  
### 4. Análise Textual
Frequência de palavras.  
Análise de sentimentos (positividade, neutralidade e negatividade).  
Complexidade textual (tamanho médio de sentenças, densidade lexical).  
### 5. Visualizações
Grafos estáticos gerados com NetworkX.  
Visualizações interativas geradas no Gephi.  

# Graficos  
## - Graus
   <img src="https://github.com/user-attachments/assets/89c2383b-8793-468e-be03-dc5ee8d39cd6" alt="BST">  
   <img src="https://github.com/user-attachments/assets/78d8a8df-403d-4628-9fc0-4d9d6ff7df26" alt="BST">  
   <img src="https://github.com/user-attachments/assets/bde235a7-cc05-40bd-ac9e-789c878600a5" alt="BST">  
   
## - PageRank  

   <img src="https://github.com/user-attachments/assets/90f001ef-44c5-4d5e-97dc-bdf6eb143b71" alt="BST">  
   <img src="https://github.com/user-attachments/assets/05897383-bcff-4b22-8a06-8d0ca7d95662" alt="BST">  
   <img src="https://github.com/user-attachments/assets/b45fdc21-b7f5-43b7-a1ba-2ceb44355d3e" alt="BST">  

## - Modularidade  

<img src="https://github.com/user-attachments/assets/3eabee20-244a-4ddf-935d-840bac5eea97" alt="BST">  
<img src="https://github.com/user-attachments/assets/62d5b016-0770-44d1-afcf-53bd021b3dc6" alt="BST">  
<img src="https://github.com/user-attachments/assets/dc530283-c015-44a3-8295-3790c0a72270" alt="BST">  

## - Centralidade de Autovetor

<img src="https://github.com/user-attachments/assets/d29caa0f-72c0-4e14-b7da-9d79392af791" alt="BST">  
<img src="https://github.com/user-attachments/assets/b10f2279-e6fc-4b39-ad41-b2359b968c50" alt="BST">  
<img src="https://github.com/user-attachments/assets/4ae63aef-bfed-4ea7-a9d0-a4a2bb34a677" alt="BST">  


# Resultados
Principais Descobertas  
Lionel Messi foi o jogador com maior centralidade de grau e PageRank.
O grafo revela comunidades bem definidas entre os jogadores da Argentina e França.
A análise textual destacou a relevância da narrativa em torno da consagração de Messi.

# Conjunto de Dados
Os dados utilizados neste trabalho foram extraídos de notícias esportivas e processados para gerar os gráficos e visualizações. Todo o código está disponível no repositório.


