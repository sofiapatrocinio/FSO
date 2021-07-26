# Processos

Um conceito fundamental para todos os sistemas operacionais é o de **processo**. É basicamente um programa em execução, que deve considerar os valores de variáveis e os valores dos registradores.

### Monoprogramação
- Um processo sendo processado por vez. 

### Multiprogramação
- Consegue intercalar processos ou programa no processador ao longo do tempo.

- Depende de um escalonador de processos: chaveia os processos de tempos em tempos. (milissegundos)

## Estados do Processo
- Executando - realmente usando a CPU naquele momento.

- Bloqueado - Incapaz de executar enquanto um evento externo não ocorrer.

- Pronto - Em memória, pronto para executar (ou para continuar sua execução), apenas aguardando a disponibilidade do processador.

### Tabela de Processos
Um arranjo (ou uma lista encadeada) de estruturas, uma para cada processo existente.

- Registradores Salvos
- Estado do processo
- ID do processo PID
- ID do proprietário
- ID Grupo
- Prioridade
- Utilização e mapeamento de memória
- Status dos arquivos abertos
- Tempo de execução cumulativo do processo