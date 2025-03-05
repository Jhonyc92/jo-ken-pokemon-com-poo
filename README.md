# Jogo Jo Ken Pokémon com Programação Orientada a Objetos
Jogo Jo Ken Pokémon com Programação Orientada a Objetos

Jogo criado em Python como forma de Nostalgia da época dos Tazos da Elma Chips de quando eu era criança

Regras: 

- Corda ganha de pedra
- Tesoura ganha de papel e corda
- Água ganha de fogo, corda, papel e tesoura
- Fogo ganha de papel, tesoura, corda e pedra
- Papel ganha de pedra, corda, tesoura e água
- Símbolos iguais resultam em empate

Versão 1.0:

- Importando o módulo 'random' para usar funções que geram valores aleatórios (necessário para a escolha do computador).

- Definindo uma classe chamada "JoKenPokemon" para encapsular a lógica e estado do jogo.

- Método construtor (__init__) da classe. Esse método é chamado automaticamente sempre que um objeto dessa classe é instanciado.

- Inicializando a pontuação do jogador como 0. 

- Inicializando a pontuação do computador como 0. 

- Inicializando uma lista com as possíveis escolhas no jogo. 

- Método para obter a escolha do jogador.

- Solicitando a escolha do jogador através da entrada do teclado. 

- Método para obter a escolha do computador.

- Método para determinar o vencedor de uma rodada, baseado nas escolhas do jogador e do computador.
