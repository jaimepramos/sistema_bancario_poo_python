# Sistema Bancário com POO em Python

Este é um projeto simples de **Sistema Bancário** desenvolvido em **Python**, utilizando conceitos de **POO (Programação Orientada a Objetos)**, como **herança, polimorfismo, abstração e encapsulamento**.  

O sistema permite a criação de clientes, abertura de contas, realização de depósitos, saques e consulta de extrato bancário.

---

## 🚀 Funcionalidades

- **Criar Cliente** (Pessoa Física com CPF, nome, data de nascimento e endereço).
- **Criar Conta Corrente** (vinculada a um cliente).
- **Depositar** em conta.
- **Sacar** valores (com limite de saques e valor máximo por saque).
- **Exibir Extrato** (listar transações realizadas e saldo atual).
- **Listar Contas** cadastradas.
- **Menu interativo** para navegação no terminal.

---

## 📂 Estrutura do Projeto

- `Cliente` → Classe base para clientes.
- `PessoaFisica` → Subclasse de Cliente.
- `Conta` → Classe base para contas bancárias.
- `ContaCorrente` → Subclasse de Conta (limite de saque e quantidade de saques).
- `Historico` → Registra todas as transações de uma conta.
- `Transacao` → Classe abstrata para transações.
- `Saque` e `Deposito` → Implementações de transações.
- Funções auxiliares para interação com usuário (criação de cliente, conta, extrato, etc).

---

## ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/jaimepramos/sistema_bancario_poo_python.git
   cd sistema-bancario
