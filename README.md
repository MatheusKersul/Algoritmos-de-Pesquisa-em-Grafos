# 🔍 Algoritmos de Pesquisa em Grafos

Aplicação Java com interface gráfica para visualização e execução de algoritmos de busca em grafos, com suporte a múltiplas representações de estrutura de dados.

---

## 📋 Funcionalidades

- **Interface gráfica** intuitiva para interação com o grafo
- **Seleção do tipo de representação** do grafo:
  - Matriz de Adjacência
  - Matriz de Incidência
  - Lista de Incidência (Lista de Adjacência)
- **Importação via arquivo `.txt`** para carregar grafos de forma prática


---

## 🧠 Algoritmos Implementados

- Busca em Profundidade (DFS)
- Busca em Largura (BFS)
- Verificação de Ciclos
- Árvore Geradora Mínima — Kruskal
- Caminho Mínimo — Dijkstra
- Caminho Mínimo — Bellman-Ford
- Fluxo Máximo — Ford-Fulkerson
- Componentes Fortemente Conectadas — Kosaraju

---

## 🗂️ Estrutura do Projeto

```
Algoritmos-de-Pesquisa-em-Grafos/
└── Algoritmos_Grafos/   # Código-fonte Java do projeto
```

---

## 🧩 Representações de Grafos

### Matriz de Adjacência
Uma matriz `n x n` onde o valor na posição `[i][j]` indica se há uma aresta entre os vértices `i` e `j`.

### Matriz de Incidência
Uma matriz `n x m` (vértices x arestas) onde cada coluna representa uma aresta e indica quais vértices ela conecta.

### Lista de Incidência (Lista de Adjacência)
Para cada vértice, é mantida uma lista dos vértices vizinhos, sendo uma representação eficiente para grafos esparsos.

---

## 📄 Formato do Arquivo de Entrada (`.txt`)

O grafo pode ser carregado por meio de um arquivo de texto. O formato esperado é:

```
<número de vértices>
<vértice origem> <vértice destino>
<vértice origem> <vértice destino>
...
```

**Exemplo:**
```
5
0 1
0 2
1 3
2 3
3 4
```

---

## 🚀 Como Executar

### Pré-requisitos

- Java JDK 8 ou superior
- IDE como IntelliJ IDEA, Eclipse, ou NetBeans (recomendado)

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/MatheusKersul/Algoritmos-de-Pesquisa-em-Grafos.git
   ```

2. Abra o projeto na sua IDE de preferência, apontando para a pasta `Algoritmos_Grafos/`.

3. Compile e execute a classe principal (`Main.java` ou equivalente).

4. Na interface gráfica:
   - Selecione o **tipo de representação** desejado
   - Carregue um grafo via arquivo `.txt` ou insira manualmente
   - Execute o algoritmo de busca

<p align="center"><img width="500" src="https://github.com/user-attachments/assets/d7de1c93-a0a4-423e-85c3-4d9057ba145f" /></p>

