# desafiobancario
lógica
# 💻 Sistema Bancário com Python

Este projeto é uma aplicação de terminal desenvolvida como desafio prático no bootcamp da [Digital Innovation One (DIO)](https://www.dio.me/). O objetivo é simular as principais operações de um sistema bancário, como 
depósitos, saques, extrato, além do 
cadastro de usuários e contas bancárias, utilizando apenas 
Python puro e estruturas de dados como listas.

A aplicação é uma excelente forma de praticar:
- Lógica de programação
- Estruturação de código com funções
- Regras de negócio financeiras
- Manipulação de dados em memória



 ✔️ Tecnologias utilizadas

- Linguagem: **Python 3**
- Interface: **Terminal (CLI)**
- Bibliotecas externas: **Nenhuma**



📑 Funcionalidades

- Criar usuários com CPF único
- Criar contas bancárias vinculadas aos usuários
- Realizar depósitos com valor válido
- Realizar saques com limite de valor e número de saques por dia
- Visualizar extrato de transações
- Listar contas cadastradas
- Menu interativo via terminal



📌 Regras de Negócio

- Cada usuário é identificado unicamente por seu CPF
- Uma conta só pode ser criada se o usuário já estiver cadastrado
- Saques têm limite de R$500,00 por operação
- São permitidos até 3 saques por dia
- Não é permitido sacar mais do que o saldo disponível
- O extrato mostra todas as movimentações da conta atual



▶️ Como executar o projeto

1. Certifique-se de ter o **Python 3** instalado na sua máquina
2. Clone este repositório:
   ```bash
   git clone https://github.com/FabianaMarquesoficial/desafiopythongit
   cd desafiopythongit

📁 Estrutura do Código
menu() – Exibe o menu principal de opções

depositar() – Realiza um depósito na conta

sacar() – Realiza um saque com validações

exibir_extrato() – Mostra as transações e saldo

criar_usuario() – Cadastra um novo usuário

criar_conta() – Cria uma conta bancária para um usuário existente

listar_contas() – Lista todas as contas criadas

💡 Melhorias Futuras
Refatoração para Programação Orientada a Objetos (POO)

Armazenamento de dados em arquivos JSON ou banco SQLite

Interface gráfica com Tkinter ou interface web com Flask

Validação de CPF e entrada de dados

🧑‍💻 Autor
Desenvolvido por FabianaMarquesoficial como parte dos desafios da Digital Innovation One.
<pre><code>```python def menu(): print("Escolha uma opção") ```</code></pre>

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
