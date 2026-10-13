# Trabalho de Inteligência Artificial — Problema dos Jarros d’Água

Implementação e comparação dos algoritmos de busca sem informação **BFS, DFS e IDS**, utilizando Python.

## 📌 Sobre o projeto

Este projeto foi desenvolvido para a disciplina de Inteligência Artificial, do curso de Análise e Desenvolvimento de Sistemas (ADS), Módulo III, do Instituto Federal do Piauí (IFPI) — Campus Picos.

O trabalho aborda o Problema dos Jarros d’Água, no qual dois jarros, com capacidades de 4 e 3 litros, devem ser utilizados para obter exatamente 2 litros de água em pelo menos um deles.

## 🎯 Objetivos

- Formalizar o problema por meio de estados, ações, estado inicial e condição objetivo.
- Implementar os algoritmos de busca em largura (BFS), busca em profundidade (DFS) e busca por aprofundamento iterativo (IDS).
- Representar graficamente os estados explorados e os caminhos encontrados.
- Comparar os algoritmos considerando a quantidade de ações e o tempo médio de execução.
- Analisar as características e a complexidade teórica de cada estratégia.

## 🧠 Algoritmos implementados

| Algoritmo | Estratégia |
|---|---|
| **BFS** — Breadth-First Search | Explora os estados por níveis e encontra o caminho com menor número de ações quando todos os custos são iguais. |
| **DFS** — Depth-First Search | Explora um caminho em profundidade antes de retornar e examinar outras possibilidades. |
| **IDS** — Iterative Deepening Search | Executa buscas limitadas em profundidade, aumentando o limite a cada iteração. |

## ⚙️ Tecnologias utilizadas

- **Python** — implementação dos algoritmos.
- **Google Colab** — ambiente de desenvolvimento e execução.
- **NetworkX** — representação dos grafos de busca.
- **Matplotlib** — visualização dos grafos e gráficos comparativos.
- **Pandas** — organização dos resultados em tabelas.

## 📊 Resultados experimentais

Na execução registrada durante o desenvolvimento, os três algoritmos encontraram uma solução com quatro ações.

| Algoritmo | Quantidade de ações | Tempo médio |
|---|---:|---:|
| BFS | 4 | 41,86 µs |
| DFS | 4 | 18,20 µs |
| IDS | 4 | 64,93 µs |

Os tempos correspondem ao ambiente e às condições da execução realizada, podendo variar em outras execuções.

O notebook também apresenta a representação gráfica dos caminhos de busca e a comparação teórica das estratégias.

## ▶️ Como executar

1. Abra o notebook `Trabalho_IA_Jarros.ipynb` disponível neste repositório.
2. Clique em **Open in Colab** ou faça o download do arquivo para abri-lo no Google Colab.
3. Execute as células na ordem apresentada.
4. Consulte os códigos, os grafos, as tabelas e as análises produzidas.

## 👩‍💻 Autoria

**Sofia Virlene Lopes Pereira**

**Instituição:** Instituto Federal do Piauí (IFPI) — Campus Picos  
**Curso:** Análise e Desenvolvimento de Sistemas (ADS)  
**Disciplina:** Inteligência Artificial — Módulo III  
**Professor:** Rogério Figueredo de Sousa

---

*Projeto acadêmico desenvolvido como atividade avaliativa da disciplina de Inteligência Artificial.*

---

*Projeto acadêmico com finalidade educacional, voltado ao estudo de algoritmos de busca sem informação.*
