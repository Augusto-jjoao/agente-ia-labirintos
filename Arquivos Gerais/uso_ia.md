# Documentação do Uso de Inteligência Artificial (IA)

Este documento relata como ferramentas de Inteligência Artificial foram utilizadas durante o desenvolvimento do agente solucionador de labirintos, destacando os momentos de avaliação crítica, correção de alucinações e validação teórica.

IA utilizada -> **Google Gemini**

## 1. Questionamento sobre a Formulação PEAS
Durante a modelagem inicial, a IA sugeriu que a formulação do problema e o modelo PEAS deveriam mudar para cada fase do trabalho (Clássica, Local e Online). Inicialmente, essa abordagem foi questionada, pois o labirinto permaneceria o mesmo. Como essa dúvida persistiu, e é sabido que a IA pode cometer erros, nosso grupo preferiu validar com o professor a respeito.

## 2. Validação das Restrições da Rubrica
Após a IA auxiliar na estruturação das classes do código Python, ela ajudou a entender se o código violava a regra de "usar apenas bibliotecas prontas de busca sem implementação própria". A IA foi utilizada para debater a diferença arquitetônica entre importar um pacote como `NetworkX`, que é proibido neste caso, e implementar o controle de fronteira iterativo usando estruturas nativas como `deque` e `heapq`. Isso garantiu que o código estava aderente às exigências do professor.

## 3. Correção de Alucinação na Leitura de Gráficos e Dados
Este foi o momento de maior intervenção humana no uso da ferramenta. Ao submeter uma imagem com gráficos de execução de um labirinto teste para validação do código, a IA "alucinou" várias e várias vezes, interpretando incorretamente os valores das barras e afirmando que o DFS havia gerado o pior caminho. 
Intervi corrigindo a IA e fornecendo os dados precisos em texto. Esse foi o maior exemplo durante o trabalho sobre não confiar na resposta gerada pela IA

## Conclusão do Uso
FAZER APÓS O FINAL DO TRABALHO