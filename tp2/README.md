# Trabalho Prático 2 - Paralelismo e Desempenho

Este trabalho foca na aplicação de técnicas de programação paralela e na avaliação de desempenho de aplicações. O objetivo é comparar as abordagens sequenciais e paralelas, verificando ganhos reais de velocidade (speedup) na execução.

## Estrutura do Trabalho

### 1. Produto Escalar (`produto_escalar`)
Cálculo de produto escalar entre vetores.
- Implementação de algoritmo sequencial tradicional.
- Implementação paralela para analisar o ganho de desempenho em processadores multi-core.

### 2. Multiplicação Matricial (`multiplicacao_matricial`)
Operação intensiva de CPU com matrizes bidimensionais.
- Comparação direta entre uma abordagem tradicional (sequencial) e uma abordagem paralela.
- Ferramenta de benchmarking incluída para facilitar a medição de tempo e a comparação do tempo de execução com os resultados gerados (`resultados_pc_12_cpu.txt`).

### 3. Simulação de Servidor Web (`simulacao_servidor_web`)
Simulação de um ambiente de servidor web lidando com requisições simultâneas.
- Servidor operando de forma sequencial (recebendo e processando uma requisição por vez na mesma thread).
- Servidor operando de forma paralela (lidando com as requisições em múltiplas threads), melhorando a taxa de vazão e o tempo de resposta geral.

## Documentação
Para a descrição completa das tarefas exigidas, detalhes técnicos e demais requisitos, consulte o arquivo de especificação **SO_TP2_2025-2.pdf**.
