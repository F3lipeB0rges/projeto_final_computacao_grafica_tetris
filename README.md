# Projeto Final de Computação Gráfica - Jogo Tetris

### Alunos: 
### Felipe Rubens de Sousa Borges
### Mateus Moraes de Moura

## Introdução 
Este relatório descreve a implementação do projeto "TETRIS com Melhorias 
Visuais" que é uma reinterpretação do clássico jogo Tetris, desenvolvido com a biblioteca 
Pygame em Python. Este trabalho visa não apenas recriar a jogabilidade tradicional, mas 
também enriquecer a experiência do usuário com elementos visuais avançados, como 
gradientes, sombras, animações e partículas. O objetivo é demonstrar a aplicação de 
técnicas de Computação Gráfica para tornar o jogo mais atraente e funcional, mantendo a 
essência do Tetris original enquanto se adicionam melhorias como menu interativo, 
sistema de pontuação com recordes, níveis de dificuldade e efeitos sonoros.

## Roteiro do Jogo 
O jogo segue uma estrutura cíclica com as seguintes etapas principais:
1. Menu Inicial: O jogador é apresentado a um menu com opções para jogar, visualizar 
recordes, ajustar a dificuldade ou sair.
2. Seleção de Dificuldade: Caso escolhida, permite ao jogador optar entre fácil, médio 
ou difícil, alterando a velocidade de queda das peças.
3. Jogabilidade: O jogador controla peças (tetrominós) que caem, podendo movê-las 
lateralmente, rotacioná-las ou acelerar sua descida, enquanto tenta completar linhas 
para ganhar pontos.
4. Game Over: Ao preencher a grade até o topo, o jogo termina, solicitando o nome do 
jogador para salvar a pontuação e o tempo no ranking de recordes.
5. Retorno ao Menu: Após o fim da partida, o jogador retorna ao menu principal para 
novas ações.

## Detalhes do Jogo
### Detalhes Gerais:
1. Tela: Resolução de 600x800 pixels, com uma grade de 10x20 blocos (cada bloco 
com 30x30 pixels).
2. Peças: Sete tetrominós clássicos (I, O, T, S, Z, L, J), cada um com uma cor distinta.
3. Controles: Setas direcionais (esquerda, direita, baixo), tecla "cima" para rotação, 
"espaço" para queda instantânea, "P" para pausar e "Q" para sair da fase.
4. Pontuação: 100 pontos por linha completada, com registro de linhas concluídas e 
tempo decorrido.
5. Dificuldade: Três níveis (fácil: velocidade 1, médio: 2, difícil: 3), ajustáveis no 
menu.
6. Efeitos Visuais: Inclui gradiente no fundo, sombra da peça, partículas ao fixar peças, 
animação de piscar ao remover linhas e texto 3D.
7. Áudio: Música tema do Tetris em loop com volume ajustado a 10%.

## Conclusões
O "TETRIS com Melhorias Visuais" combina com sucesso a jogabilidade clássica 
com técnicas modernas de Computação Gráfica, resultando em uma experiência visualmente 
rica e interativa. A implementação de gradientes, sombras e partículas eleva o apelo estético, 
enquanto animações e texto 3D reforçam a imersão. A estrutura modular do código facilita 
expansões futuras, como novos efeitos ou modos de jogo. Contudo, há espaço para 
melhorias, como otimização de desempenho em animações complexas e adição de mais 
opções de personalização (ex.: temas visuais). O projeto demonstra o potencial da 
Computação Gráfica em revitalizar jogos tradicionais, oferecendo uma base sólida para 
estudos ou desenvolvimentos adicionais
