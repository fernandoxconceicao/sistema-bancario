# Sistema Bancário Simples

Este é um projeto simples de sistema bancário desenvolvido em Python, que permite ao usuário realizar operações básicas como depósito, saque, visualizar extrato e sair do sistema.

## Funcionalidades

- **Depósito:** Permite adicionar saldo à conta.
- **Saque:** Permite retirar saldo da conta, respeitando o limite de valor e quantidade de saques diários.
- **Extrato:** Exibe todas as movimentações realizadas e o saldo atual.
- **Sair:** Encerra o programa.

## Como usar

1. **Clone este repositório ou copie o código para um arquivo chamado `banco.py`.**
2. **Execute o arquivo em seu terminal:**
   ```bash
   python banco.py
   ```
3. **Siga as instruções do menu para realizar as operações desejadas.**

## Exemplo de uso

```
[d] Depositar
[s] Sacar
[e] Extrato
[q] Sair

=> d
Informe o valor do depósito: 100

=> s
Informe o valor do saque: 50

=> e

================ EXTRATO ================
Depósito: R$ 100.00
Saque: R$ 50.00

Saldo: R$ 50.00
==========================================
```

## Regras do sistema

- O limite de saque por operação é de R$ 500,00.
- O número máximo de saques diários é 3.
- Não é permitido sacar valores superiores ao saldo disponível.
- Não é permitido depositar ou sacar valores negativos ou zerados.

## Requisitos

- Python 3.x

## Licença

Este projeto está sob a licença MIT.
