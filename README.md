# 🕹️ Tic tac toe in python

This is a simple tic-tac-toe game implemented in **Python**  to be directed playtd in the terminal.  
Two players alternate between them, using `x` and `o`, choosing the positions from **1 to 9** in the board until someone win or it draws.

---

## 🚀 How to play

1. Clone or download this repository
   ```bash
   git clone https://github.com/seu-usuario/jogo-da-velha-python.git

2. Run the file:

   ```bash
   python app.py
   ```
3. The program will display the board numbered from 1 to 9:

   ```
   1 | 2 | 3
   ---------
   4 | 5 | 6
   ---------
   7 | 8 | 9
   ```
4. The current player must type the number corresponding to the desired position.
5. The game ends when:

   * A player aligns **3 symbols** (in a row, column, or diagonal);
   * Or when all positions are filled (draw).

---

## 📂 Code Structure

* **mostrar\_tabuleiro(tab)** → displays the updated board.
* **verificar\_vitoria(tab, jogador)** → checks if the current player has won.
* **main loop** → controls rounds, alternates players, and checks for victory or draw.

---

## 📸 Example Gameplay

```
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9

Player X, choose a position (1-9): 5

1 | 2 | 3
---------
4 | X | 6
---------
7 | 8 | 9
```

---

## 🛠️ Technologies Used

* **Python 3.x**

---

## ✨ Future Improvements

* Add a **computer mode (simple AI)**;
* Create a **graphical interface** using Tkinter or Pygame;
* Improve input validation for invalid entries.

---

📌 Have fun playing! 😃

---



# 🕹️ Jogo da Velha em Python

Este é um simples jogo da velha implementado em **Python** para ser jogado diretamente no terminal.  
Dois jogadores se alternam utilizando `X` e `O`, escolhendo as posições de **1 a 9** no tabuleiro até que alguém vença ou dê empate.

---

## 🚀 Como jogar

1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/seu-usuario/jogo-da-velha-python.git

2. Execute o arquivo:

   ```bash
   python app.py
   ```
3. O programa exibirá o tabuleiro numerado de 1 a 9:

   ```
   1 | 2 | 3
   ---------
   4 | 5 | 6
   ---------
   7 | 8 | 9
   ```
4. O jogador da vez deve digitar o número correspondente à posição desejada.
5. O jogo termina quando:

   * Um jogador consegue alinhar **3 símbolos** (em linha, coluna ou diagonal);
   * Ou quando todas as casas forem preenchidas (empate).

---

## 📂 Estrutura do código

* **mostrar\_tabuleiro(tab)** → exibe o tabuleiro atualizado.
* **verificar\_vitoria(tab, jogador)** → verifica se o jogador atual venceu.
* **loop principal** → controla as rodadas, alterna jogadores e verifica se há vencedor ou empate.

---

## 📸 Exemplo de execução

```
1 | 2 | 3
---------
4 | 5 | 6
---------
7 | 8 | 9

Jogador X, escolha uma posição (1-9): 5

1 | 2 | 3
---------
4 | X | 6
---------
7 | 8 | 9
```

---

## 🛠️ Tecnologias utilizadas

* **Python 3.x**

---

## ✨ Melhorias futuras

* Adicionar **modo contra o computador (IA simples)**;
* Criar uma **interface gráfica** com Tkinter ou Pygame;
* Melhorar a validação de entradas inválidas.

---

📌 Divirta-se jogando! 😃

---
