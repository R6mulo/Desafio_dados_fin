# 🏦 Desafio

Projeto desenvolvido durante o curso **"Java: Criando sua primeira aplicação"** da trilha **Back-End na ONE - Oracle Next Education**.  
O desafio consiste em criar uma aplicação simples de **controle bancário**, simulando operações básicas como depósito, saque e consulta de saldo.

---

## 🔨 Objetivos do Projeto

O programa deve:

- Exibir um **cabeçalho inicial** com os dados do cliente:
  - Nome
  - Tipo da conta
  - Saldo inicial

- Exibir um **menu interativo** com as opções:

  **1**. **Consultar saldo**  
  **2**. **Receber valor** (depósito, transferência ou Pix)  
  **3**. **Transferir valor** (saque, envio de Pix)  
  **4**. **Sair da aplicação**  

- Garantir que:
  - O menu permaneça ativo até o usuário escolher a opção de **sair**.
  - Não seja possível sacar valores **maiores que o saldo disponível**.
  - Seja exibida uma mensagem de **opção inválida** caso o usuário insira uma entrada incorreta.

---

## 🧩 Tecnologias Utilizadas

- **Java SE**
- **Classe Scanner** (para leitura de entradas do usuário)
- **Estruturas de decisão e repetição**
- **IDE** de sua preferência (Eclipse, IntelliJ, VS Code etc.)

---

## 💻 Funcionalidades

| Função              | Descrição                                                                 |
|---------------------|---------------------------------------------------------------------------|
| `consultarSaldo()`  | Mostra o saldo atual da conta.                                            |
| `receberValor()`    | Adiciona um valor ao saldo (depósito ou transferência recebida).          |
| `transferirValor()` | Remove um valor do saldo (saque, envio de Pix ou transferência).          |
| `menu()`            | Exibe o menu de opções até o usuário encerrar a aplicação.                |

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/R6mulo/Desafio_dados_fin.git

## 👨‍💻 Autor

**Romulo Chaves**  
📚 Estudante do programa **ONE Oracle Next Education**  
🔗 [GitHub](https://github.com/r6mulo) • [LinkedIn](https://linkedin.com/in/romulo-chaves)
