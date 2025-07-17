# **Sudoku em Java 21**

Este projeto é uma implementação do jogo Sudoku utilizando Programação Orientada a Objetos (POO) em **Java**.

Com uma abordagem simples e prática, o projeto explora conceitos importantes de programação, como estrutura de dados, manipulação de objetos e interação com o usuário.

## 📌 **Funcionalidades**

- **🎮 Jogo Interativo:** O jogador pode interagir com o jogo, colocando e removendo números nas células, além de visualizar o estado atual do tabuleiro.
- **✅ Verificador de Solução:** O sistema valida a solução inserida, indicando se o jogo foi completado corretamente ou se contém erros.
- **🔄 Reiniciar e Limpar Jogo:** O jogador pode reiniciar o jogo ou limpar os valores inseridos, caso necessário.
- **🚀 Status do Jogo:** O jogo exibe informações sobre o progresso, como se está completo, incompleto ou não iniciado.

## 🛠 **Tecnologias Utilizadas**

- **☕ Java:** Linguagem de programação principal para o desenvolvimento do jogo.
- **🖥 Swing:** Biblioteca gráfica utilizada para a criação da interface do usuário (GUI).

## 🗂 **Arquitetura do Projeto**

A estrutura do projeto foi organizada para garantir uma separação clara de responsabilidades e facilitar a manutenção e evolução do código:

### **Detalhamento das Pastas:**

- **`model/`**: Contém as classes que representam a lógica do jogo, como `Board` (Tabuleiro), `Space` (Espaços do Sudoku) e `GameStatusEnum` (Status do jogo).
- **`view/`**: Contém a interface gráfica utilizando o Swing para permitir que o jogador interaja com o jogo. (Ainda em desenvolvimento, caso seja necessário expandir a GUI).
- **`controller/`**: Contém as classes responsáveis por gerenciar a lógica de interação do jogo, como a inserção de números e a verificação de erros no tabuleiro.

## 🧑‍💻 **Como Executar o Projeto**

Para rodar o projeto em sua máquina local, siga as instruções abaixo:

### 1. **Pré-requisitos:**
   - Certifique-se de ter o **Java 21** instalado. Você pode verificar isso executando:
     ```bash
     java -version
     ```

### 2. **Clonando o Repositório:**
   Clone o repositório para a sua máquina local:
   ```bash
   git clone https://github.com/usuario/sudoku-java.git
   cd sudoku-java

### 3. **Executando o jogo:**
 mvn exec:java
