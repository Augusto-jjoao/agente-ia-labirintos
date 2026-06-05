# Agente Inteligente - Resolução de Labirintos

Repositório dedicado ao desenvolvimento de um agente autônomo para navegação em labirintos para a disciplina de Inteligencia Artificial na Universidade Federal de Ouro Preto. O projeto explora os fundamentos de IA e agentes inteligentes, e é dividido em três fases de complexidade: Busca Clássica (mapa conhecido), Busca Local (múltiplos objetivos) e Busca Online (mapa desconhecido).

## Tecnologias Utilizadas
* **Python 3**
* **Jupyter Notebook**
* **Pandas** (Estruturação e exportação de dados)
* **Matplotlib** (Visualização de métricas e gráficos)

## Fase 1: Busca Clássica
Implementação nativa de algoritmos clássicos para encontrar rotas em um ambiente de custo uniforme. Os algoritmos usados foram:
* Busca em Largura (BFS)
* Busca em Profundidade (DFS)
* Busca de Custo Uniforme (UCS)
* Busca Gulosa (Greedy Best-First)
* Busca A* (com Heurística de Manhattan)
* Busca IDA* (utilizada principalmente para otimização e para evitar estouro de pilha de memória)

É importante ressaltar que, para fins didáticos, não foram usadas bibliotecas nativas dos algoritmos.

## 📁 Estrutura do Repositório
ARQUIVOS SEMANA 1
* `scriptSemana1.ipynb`: Notebook principal com toda a implementação de código referente a fase 1 (busca clássica).
* `lab_oficial.txt`: Arquivo contendo o labirinto para o trabalho.
* `resultados_semana1.csv`: Métricas brutas exportadas para a fase de busca clássica (Nós Expandidos, Explorados e Tamanho do Caminho).
--
ARQUIVOS SEMANA 2

--
ARQUIVOS SEMANA 3

--
ARQUIVOS GERAIS
* `Relatorio_Tecnico.pdf`: Análise crítica comparando a otimalidade e o trade-off de tempo/memória dos algoritmos.
* `uso_ia.md`: Documentação das validações teóricas e auditoria do uso de IA durante o desenvolvimento.

## Como Executar
1. Clone este repositório: `git clone URL_DO_SEU_REPO`
2. Abra o arquivo `.ipynb` em um ambiente Jupyter (JupyterLab, VS Code ou Google Colab).
3. Certifique-se de que o arquivo de mapa (`lab_oficial.txt`) esteja no mesmo diretório.
4. Execute as células sequencialmente para visualizar a tabela de resultados e os gráficos comparativos.

---