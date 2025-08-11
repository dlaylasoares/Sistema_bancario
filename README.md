# Sistema Bancário em Python

Este projeto é um sistema bancário simples desenvolvido em **Python**, com funcionalidades de depósito, saque, extrato, cadastro de usuários e contas.  
O código segue uma estrutura modular, com funções separadas para cada operação, facilitando a manutenção e a evolução do sistema.

## 📌 Funcionalidades

- **Depósito**: Permite adicionar saldo à conta, com registro no extrato.
- **Saque**: Realiza saques com verificação de:
  - Saldo suficiente
  - Limite de saque por operação
  - Limite diário de número de saques
- **Extrato**: Exibe todas as movimentações e o saldo atual.
- **Cadastro de usuário**: Registra novos clientes no sistema.
- **Cadastro de conta**: Cria contas vinculadas a usuários existentes (um CPF só pode ter uma conta).
- **Listagem de contas**: Exibe todas as contas cadastradas no sistema.

## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**
- Biblioteca padrão (`textwrap`)
