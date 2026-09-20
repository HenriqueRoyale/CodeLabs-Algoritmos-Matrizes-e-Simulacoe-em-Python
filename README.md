# 🧪 CodeLabs: Algoritmos, Matrizes e Simulações em Python

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-3776AB.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Algorithms](https://img.shields.io/badge/Algorithms-Recursion%20%26%20DP-2ca02c.svg?style=for-the-badge)](#)
[![Data Structures](https://img.shields.io/badge/Data%20Structures-Matrices%20%26%20Arrays-150458.svg?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

> Uma coleção de laboratórios e desafios de programação focados no desenvolvimento de algoritmos complexos, manipulação de estruturas de dados bidimensionais (matrizes) e otimização de rotinas computacionais. Este repositório demonstra a aplicação prática de conceitos como **Programação Dinâmica**, **Recursividade** e **Parsing de Strings**.

---

## 🎯 Sobre o Projeto

Este repositório consolida cinco projetos/laboratórios distintos, cada um resolvendo um problema computacional específico através de modelação matemática e lógica de programação. Desde a navegação espacial num ambiente 3D até à síntese de sequências biológicas, o foco mantém-se na eficiência e na resolução criativa de problemas.

### 🌟 Destaques dos Laboratórios (Módulos)

*   🧬 **Lab 14: Sintetizador de DNA (Programação Dinâmica)**
    Um algoritmo avançado que utiliza recursividade com *memoização* (armazenamento de estados pré-calculados em dicionários) para transformar uma sequência genética inicial noutra final[cite: 8]. O motor avalia diferentes reagentes, mutações e custos associados, garantindo que a transformação não excede o orçamento máximo estipulado[cite: 8].
*   🏢 **Lab 15: Otimizador de Limpeza (Pathfinding Recursivo)**
    Simula a rota de um robô limpa-vidros na fachada de um edifício[cite: 7]. O script calcula os custos de movimentos horizontais e verticais entre diferentes faces do prédio (Norte, Sul, Este, Oeste), utilizando buscas recursivas para determinar se é possível limpar todas as janelas sujas dentro de um limite de movimentos (`c`)[cite: 7].
*   🤖 **Lab 11: Robô Navegador 3D (Matrizes Interligadas)**
    Implementa a movimentação tridimensional de um robô numa grelha que representa as quatro faces de um edifício[cite: 9]. O sistema rastreia a posição (Andar e Janela) e processa comandos de direção (Cima, Baixo, Esquerda, Direita), transferindo a entidade de forma fluida entre as diferentes faces matriciais e imprimindo o estado final da simulação[cite: 9].
*   🎱 **Lab 10: Motor de Bingo (Validação 2D)**
    Um motor de jogo focado em validação de matrizes 5x5[cite: 10]. O algoritmo processa as "pedras" sorteadas em tempo real, atualizando uma matriz de marcação e inspecionando ciclicamente as linhas, colunas e ambas as diagonais (principal e secundária) para detetar o momento exato da vitória e imprimir os números vencedores[cite: 10].
*   🧮 **Lab 09: Cifra e Calculadora Alfanumérica**
    Um conversor de *strings* que mapeia letras do alfabeto para valores numéricos baseados num dicionário customizável[cite: 11]. O programa faz o *parsing* posicional (Base 10) de palavras inteiras, convertendo frases em grandes números, e resolve expressões matemáticas (somas e subtrações) diretamente a partir do texto lido[cite: 11].

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.10+
- **Paradigma:** Funcional e Procedimental
- **Conceitos Chave:**
  - *Memoization* e Otimização de Recursão[cite: 8]
  - Manipulação de Matrizes e *Arrays* Bidimensionais[cite: 9, 10]
  - Lógica de Modulação e Roteamento Circular (Travessia de bordas)[cite: 9]
  - *Parsing* e Conversão de Tipos (Strings para Int em lógicas de Base 10)[cite: 11]

---

## 📂 Estrutura do Repositório

```text
CodeLabs-Python/
├── lab09.py       # Calculadora de palavras e manipulação de dicionários
├── lab10.py       # Validador matricial para jogo de Bingo 5x5
├── lab11.py       # Simulação de travessia em matrizes interligadas (Faces)
├── lab14.py       # Sintetizador DNA com programação dinâmica e cache
├── lab15.py       # Otimizador recursivo de trajetórias com limites de custo
└── README.md      # Documentação central do projeto
