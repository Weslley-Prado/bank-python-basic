## Menu da Conta Bancária

Este trecho de código representa um menu simples de conta bancária que permite aos usuários realizar operações como depósito, saque, verificar o extrato da conta e sair.

### Variáveis

- `saldo`: Representa o saldo atual da conta.
- `limite`: Representa o limite de saque.
- `extrato`: Armazena o histórico de transações.
- `numero_saque`: Controla o número de saques realizados.
- `LIMITE_SAQUES`: Representa o número máximo de saques permitidos.

### Opções do Menu

- `d` - Depositar: Permite ao usuário depositar dinheiro na conta.
- `s` - Sacar: Permite ao usuário sacar dinheiro da conta.
- `e` - Extrato: Exibe o histórico de transações e saldo atual.
- `q` - Sair: Encerra o programa.

### Loop Principal

O código é executado em um loop infinito até que o usuário escolha sair (`q`). Cada opção é tratada da seguinte forma:

- Opção `d` (Depositar): Solicita ao usuário o valor do depósito e atualiza o saldo da conta.
- Opção `s` (Sacar): Solicita ao usuário o valor do saque e realiza verificações necessárias antes de atualizar o saldo da conta.
- Opção `e` (Extrato): Imprime o histórico de transações e o saldo atual da conta.
- Opção `q` (Sair): Interrompe o loop e encerra o programa.
