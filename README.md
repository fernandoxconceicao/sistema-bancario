# Sistema Bancário em Python (OOP)

Este projeto é um sistema bancário simples, desenvolvido em Python, utilizando conceitos de **Programação Orientada a Objetos** (POO). O sistema permite criar clientes, contas, realizar depósitos, saques, consultar extratos e listar contas, tudo de forma interativa pelo terminal.

## Funcionalidades

- **Cadastro de clientes** (Pessoa Física)
- **Criação de contas correntes** para clientes existentes
- **Depósito** em conta
- **Saque** com limite de valor e quantidade
- **Extrato** de movimentações e saldo
- **Listagem de contas** cadastradas
- **Registro de transações** com data/hora
- **Logs automáticos** das operações realizadas

## Como usar

1. **Salve o código em um arquivo chamado `banco.py`.**
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

## Principais Classes e Estruturas

- **Cliente / PessoaFisica:** Representa o cliente do banco.
- **Conta / ContaCorrente:** Representa a conta bancária, com histórico de transações.
- **Transacao / Saque / Deposito:** Hierarquia para registrar operações financeiras.
- **Historico:** Armazena todas as transações realizadas na conta.
- **ContasIterador:** Permite iterar e exibir todas as contas cadastradas.
- **Decorador de log:** Registra data/hora de cada operação.

## Regras do sistema

- O limite de saque por operação é de R$ 500,00.
- O número máximo de saques diários é 3.
- Não é permitido sacar valores superiores ao saldo disponível.
- Não é permitido depositar ou sacar valores negativos ou zerados.
- Para criar uma conta, o cliente deve estar cadastrado (CPF único).
- Cada conta possui um número único e está vinculada a um cliente.

## Requisitos

- Python 3.x

## Licença

Este projeto está sob a licença MIT.

