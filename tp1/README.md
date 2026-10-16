# Trabalho Prático 1 - Sincronização e Concorrência

Este trabalho tem como objetivo explorar e resolver problemas clássicos de sincronização de processos em Sistemas Operacionais, demonstrando na prática as consequências da falta de controle de concorrência e como corrigi-las.

## Estrutura do Trabalho

### 1. Leitores e Escritores (`leitores_escritores`)
Implementação do problema clássico de leitores e escritores, onde múltiplas threads tentam acessar um recurso compartilhado.
- Demonstração do problema sem controle de concorrência (gerando leitura suja/inconsistente).
- Solução utilizando mecanismos de controle adequados para garantir a integridade e consistência dos dados.

### 2. Produtores e Consumidores (`produtores_consumidores`)
Implementação do problema do produtor-consumidor utilizando buffers compartilhados.
- Versões com apenas 1 consumidor e múltiplas threads produtoras.
- Versões com múltiplos produtores e múltiplos consumidores concorrendo pelo buffer.
- Demonstração dos efeitos colaterais da ausência de sincronização apropriada.

## Documentação
Para mais detalhes sobre as decisões de projeto e análises de resultados realizadas durante o trabalho, consulte o arquivo **Relatório.pdf** e o documento de especificação da atividade, **SO_TP1_2025-2.pdf**.
