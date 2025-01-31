# Chess System Java

##
[![NPM](https://img.shields.io/bower/l/react)](https://github.com/vitorbnr/chess-system-java/blob/main/LICENSE)

# Projeto de Xadrez em Java ♟️

Este projeto tem como objetivo fixar o aprendizado da linguagem Java através da construção de um jogo de xadrez totalmente jogável via console (IDE ou linha de comando). O desenvolvimento desse sistema de xadrez envolveu a aplicação de conceitos fundamentais de programação orientada a objetos e estruturas de controle em Java.

## Objetivos do Projeto 🎯

O projeto foi criado como uma forma de consolidar e aplicar o conhecimento adquirido durante o estudo da linguagem Java. A implementação do xadrez em console oferece uma maneira prática de trabalhar com diversos recursos da linguagem, proporcionando uma experiência rica de aprendizado.

## Tecnologias e Conceitos Aplicados 💻

Durante o desenvolvimento, os seguintes tópicos e conceitos de Java foram explorados e aplicados:
- **Classes e Objetos**: Criação de classes representando as peças e o tabuleiro, com atributos e comportamentos específicos.
- **Métodos**: Definição de métodos para controlar o comportamento das peças e a lógica do jogo.
- **Listas**: Uso da coleção List para gerenciar as peças capturadas e os movimentos.
- **Matrizes**: Representação do tabuleiro de xadrez utilizando uma matriz bidimensional.
- **Estruturas de Repetição e Controle de Fluxo**: Controle do fluxo do jogo através de laços `for`, `while` e condições `if-else`.
- **Instanciação de Classes**: Instanciamento dinâmico das peças no tabuleiro.
- **Blocos Try/Catch**: Manipulação de exceções durante a execução do jogo para garantir robustez.
- **Tratamento de Exceções**: Implementação de tratamentos para erros e situações inesperadas durante o jogo.
- **Herança e Polimorfismo**: Criação de uma hierarquia de classes para as peças de xadrez, aproveitando a reutilização de código e comportamento específico de cada peça.

## Como Jogar 🎮

O jogo pode ser executado diretamente no console da IDE ou através da linha de comando. Após iniciar o jogo, os jogadores se alternam inserindo os movimentos das peças no formato adequado. O tabuleiro será atualizado a cada movimento, e o sistema verificará automaticamente as regras do xadrez, como movimento válido, captura de peças e xeque.

## Como Executar 🚀

Para executar o projeto em sua máquina, siga os passos abaixo:

1. **Clone o repositório**: Abra o terminal ou o prompt de comando e execute o comando abaixo para clonar o repositório localmente:
   ```bash
   git clone https://github.com/vitorbnr/chess-system-java.git
Navegue até o diretório do projeto: Após o clone ser concluído, entre no diretório do projeto:

cd chess-system-java

Compile o projeto: Se você estiver usando o terminal, você pode compilar os arquivos Java com o comando abaixo:

javac application/Program.java

Execute o projeto no terminal: Após a compilação, navegue para a pasta out, depois production, depois chess-system-java e execute o comando:

java application.Program

Execute o projeto na IDE: Abra sua IDE (por exemplo, IntelliJ IDEA), importe o projeto e execute a classe Program.java dentro do pacote application.

Instruções de Uso 📋
Movimentos: O jogo permite que dois jogadores controlem as peças de xadrez diretamente pelo console. Os movimentos são realizados digitando as coordenadas das peças (em formato de notação xadrez), como por exemplo: e2 e4 para mover um peão da casa e2 para a casa e4.

Fluxo do Jogo: O tabuleiro será mostrado no console a cada jogada, com as posições atualizadas das peças. O sistema verifica automaticamente se o movimento é válido ou se há captura de peças. O jogo segue as regras oficiais de xadrez, incluindo cheque e xeque-mate.

Finalização: O jogo termina quando um dos jogadores dá xeque-mate ou ocorre um empate conforme as regras do xadrez.

Aprendizados 📚
Este projeto foi fundamental para fortalecer os seguintes conceitos:

Lógica de programação aplicada a um cenário real (jogo de xadrez).

Modelagem orientada a objetos, representando cada peça como uma entidade com comportamento próprio.

Gerenciamento de fluxos complexos, como o ciclo de turnos e a verificação de estados do jogo (xeque, xeque-mate, empate).

Tratamento de exceções, tornando o jogo mais robusto e seguro contra entradas inválidas.

