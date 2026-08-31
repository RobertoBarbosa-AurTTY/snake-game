# 🐍 Snake Game

Um jogo clássico da cobrinha (Snake) desenvolvido em **Java** com **Swing**, construído usando **Maven**.

## 🛠️ Tecnologias

- Java 19
- Swing (GUI)
- Maven

## 🚀 Como executar

Clone o repositório:

```bash
git clone https://github.com/RobertoBarbosa-AurTTY/snake-game.git
cd snake-game
```

Compile e execute com Maven:

```bash
mvn compile
mvn exec:java
```

Ou, se preferir, execute diretamente pela classe principal:

```bash
mvn exec:java -Dexec.mainClass="snake.Snake"
```

## 🎮 Como jogar

- Use as **setas do teclado** para mover a cobra
- Coma a comida para crescer
- Evite colidir com o próprio corpo

## 🗂️ Estrutura do projeto

```
src/main/java/snake/
├── Snake.java      # Classe principal (entry point)
├── GameFrame.java  # Janela principal do jogo
└── GamePane.java   # Painel com a lógica e renderização do jogo
```

## 📄 Licença

Este projeto está sob a licença MIT.
