# Sistema Bancário em Python

Este é um projeto de sistema bancário simples, desenvolvido em Python, que permite criar usuários, contas bancárias, realizar depósitos, saques, consultar extrato e listar contas.

## Funcionalidades

- **Depósito:** Realize depósitos em sua conta.
- **Saque:** Saque valores respeitando o limite diário e por operação.
- **Extrato:** Consulte todas as movimentações e o saldo atual.
- **Novo Usuário:** Cadastre novos usuários no sistema.
- **Nova Conta:** Crie contas bancárias para usuários já cadastrados.
- **Listar Contas:** Veja todas as contas cadastradas no sistema.
- **Sair:** Encerre o programa.

## Como usar

1. **Clone este repositório ou copie o código para um arquivo chamado `banco.py`.**
2. **Execute o arquivo no terminal:**
   ```bash
   python banco.py
   ```
3. **Siga as instruções do menu para realizar as operações desejadas.**

## Exemplo de uso

```
================ MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=>
```

## Regras do sistema

- O limite de saque por operação é de R$ 500,00.
- O número máximo de saques diários é 3.
- Não é permitido sacar valores superiores ao saldo disponível.
- Não é permitido depositar ou sacar valores negativos ou zerados.
- Para criar uma conta, o usuário deve estar cadastrado no sistema (CPF único).
- Cada conta possui um número único e está vinculada a um usuário.

## Requisitos

- Python 3.x

## Licença

Este projeto está sob a licença MIT.
