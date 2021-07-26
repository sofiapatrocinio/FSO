# Chamadas de Sistema e Interrupção

- Se uma aplicação precisa realizar alguma instrução privilegiada, ela realiza uma chamada de sistema, que altera do modo usuário para o modo kernel.

- Chamadas de sistema são a porta de entrada para o modo kernel.

- As chamadas de sistemas são realizadas através de instruções **Traps**.

- Traps são conhecidos como interrupções de software.

- Após o término da chamada, a execução continua após a chamada de sistema.

## Passos para Chamada de Sistema

1. Aplicativo faz a chamada ao sistema (Trap).

2. Através de uma tabela, o SO determina o endereço da rotina.

3. Rotina de serviço é acionada (rotina compartilhada).

4. Serviço solicitado é executado e o controle retorna ao aplicativo.