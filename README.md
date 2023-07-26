# restaurante
 # Operação Bancária em Python

Este é um projeto simples de uma Operação Bancária em Python. O sistema foi desenvolvido para permitir a realização de operações básicas em uma conta bancária, como depósito, saque e consulta de saldo. Além disso, os usuários podem criar contas correntes ou poupanças e fornecer informações de endereço.

## Funcionalidades

- **Depósito**: Permite adicionar um valor ao saldo da conta bancária.
- **Saque**: Permite sacar um valor da conta, respeitando o limite diário de 23 saques e o limite máximo de R$500,00 por saque. Caso o saldo seja insuficiente, o saque não é permitido.
- **Consulta de Saldo**: Exibe o saldo atual da conta bancária.
- **Extrato**: Imprime o extrato da conta, mostrando todas as transações realizadas, incluindo depósitos e saques.

## Cadastro de Usuário e Conta

Ao iniciar o programa, o usuário tem a opção de cadastrar um novo cliente. O cadastro requer as seguintes informações:

1. CPF do cliente: utilizado para identificar o usuário.
2. Endereço: endereço completo do cliente, incluindo bairro, estado e cidade.

O sistema verifica se o CPF já está cadastrado para outro cliente, garantindo que não haja duplicações. Além disso, o usuário pode escolher entre criar uma conta corrente ou poupança.

## Utilização

Para utilizar a Operação Bancária em Python, siga as instruções abaixo:

1. Ao iniciar o programa, uma conta bancária é criada automaticamente com um saldo inicial de R$1000,00.

2. O usuário verá um menu com as seguintes opções:

   Menu:

   1. Cadastrar Usuário e Conta
   2. Consultar Saldo
   3. Realizar Depósito
   4. Realizar Saque
   5. Imprimir Extrato
   0. Sair

3. Para escolher uma opção, basta digitar o número correspondente no teclado e pressionar "Enter".

4. Para realizar um depósito (opção 3) ou um saque (opção 4), o sistema solicitará ao usuário que insira o valor desejado.

5. O extrato (opção 5) exibirá todas as transações realizadas na conta, incluindo depósitos e saques.

6. Para sair do programa, basta escolher a opção 0.

## Observações

- O sistema controla o número de saques realizados em um dia, respeitando o limite diário de 23 saques.
- O valor máximo permitido para cada saque é de R$500,00.
- Caso o usuário tente sacar um valor superior ao saldo disponível na conta, o sistema exibirá uma mensagem informando que não é possível realizar o saque por falta de saldo.

Esperamos que esta Operação Bancária em Python seja útil para realizar operações bancárias básicas e que contribua para o seu aprendizado em Python.

## Autor

Este projeto foi desenvolvido por(https://github.com/SciDevPablo).

