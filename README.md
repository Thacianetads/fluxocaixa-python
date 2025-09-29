# 📊 Fluxo de Caixa em Python

Um script simples em Python para registrar receitas e despesas, calculando o saldo final ao encerrar o programa.

# ✨ Funcionalidades

- Adição de receitas

- Adição de despesas

- Exibição de todas as transações

- Cálculo automático do saldo final

# 💡 Como funciona

O script oferece um menu interativo via terminal, onde você pode:

1. Adicionar uma receita

2. Adicionar uma despesa

3. Encerrar o programa e exibir o resumo do fluxo de caixa

4. Cada transação inclui um nome (descrição) e um valor. Ao encerrar, o programa imprime todas as transações e o saldo atual.

# ▶️ Como executar

- Certifique-se de ter o Python 3 instalado.

- Clone o repositório ou copie o código para um arquivo chamado main.py.

- Execute o arquivo via terminal: python main.py

# 💻 Exemplo de uso
  ____________
  @ Fluxo caixa
  ____________
  1 - Adicionar receita

  2 - Adicionar despesa
  _____________
  #Digite outro numero para encerrar#
  _____________  

  Digite a opcao: 1

  Nome: Salário

  Valor: 3000
  _____________

  Digite a opcao: 2

  Nome: Aluguel

  Valor: -1200
  _____________

  Digite a opcao: 9

  Nome: Salário , Valor: R$ 3000.0

  Nome: Aluguel , Valor: R$ -1200.0

  Saldo atual: R$ 1800.0
  

# 📁 Estrutura do Código

- fluxo_caixa: lista que armazena todas as transações

- adicionar_transacao(): função que solicita dados do usuário e adiciona à lista

- while True: laço principal para capturar as opções do menu

- Impressão final: mostra todas as transações e calcula o saldo
