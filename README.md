# Sistema Bancário em POO

## 📌 Objetivo Geral
Este projeto tem como objetivo **iniciar a modelagem de um sistema bancário utilizando Programação Orientada a Objetos (POO)** em Python.  
O sistema permite gerenciar **clientes, contas bancárias e operações de saque e depósito**, seguindo as boas práticas de abstração e encapsulamento.

## 🏗️ Modelagem UML
O sistema foi modelado com base no seguinte diagrama UML:  

![Diagrama UML](diagrama.png)

### Principais entidades:
- **Cliente / Pessoa Física**: Representa os clientes do banco.
- **Conta / Conta Corrente**: Gerencia saldo, limite e movimentações.
- **Transação (Interface)**: Interface para operações financeiras.
  - **Depósito**
  - **Saque**
- **Histórico**: Registra todas as transações realizadas.

---

## 🔧 Funcionalidades
- Criar clientes e contas bancárias.  
- Realizar **depósitos** e **saques**.  
- Controlar **limite de saque** e **quantidade de operações diárias** em conta corrente.  
- Armazenar **histórico de transações** (com data, tipo e valor).  
