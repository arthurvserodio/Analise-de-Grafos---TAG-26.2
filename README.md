# 🌐 Análise de Rede Social com Teoria dos Grafos (TAG)

> Projeto desenvolvido para a disciplina de Teoria e Aplicação de Grafos, com o objetivo de analisar uma rede social real do Facebook utilizando técnicas avançadas de ciência de dados e teoria de grafos.

---

## 📊 Sobre o Projeto

Este projeto explora a estrutura e a dinâmica de conexões de uma rede social. Através da modelagem dos dados como um grafo, foram investigados padrões de relacionamento, nós influentes e subestruturas (comunidades) utilizando algoritmos modernos em Python.

---

## 🚀 Tecnologias e Ferramentas

As principais bibliotecas utilizadas no desenvolvimento da análise foram:
* **[Python](https://www.python.org/)**: Linguagem principal do projeto.
* **[NetworkX](https://networkx.org/)**: Criação, manipulação e análise da estrutura dos grafos.
* **[Pandas](https://pandas.pydata.org/)**: Manipulação e limpeza dos dados tabulares.
* **[python-louvain](https://github.com/taynaud/python-louvain)**: Algoritmo de detecção de comunidades.
* **[Gephi](https://gephi.org/)**: Visualização avançada e exploração interativa da rede.

---

## 🔍 Principais Análises Realizadas

* **Métricas Estruturais Básicas**: Cálculo do número de nós, arestas, grau médio, densidade e diâmetro da rede.
* **Métricas de Centralidade**: Identificação dos atores mais importantes/influentes através de:
  * Centralidade de Grau (*Degree Centrality*)
  * Centralidade de Intermediação (*Betweenness Centrality*)
  * Centralidade de Proximidade (*Closeness Centrality*)
  * *PageRank*
* **Detecção de Comunidades**: Aplicação do **Método de Louvain** para particionar a rede em grupos coesos e analisar a modularidade.

