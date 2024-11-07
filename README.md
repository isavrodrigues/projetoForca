# Jogador de Forca 

## Objetivo


## Conceitos Utilizados

### Entropia
A entropia mede a incerteza do sistema e é usada para calcular a importância das letras no vocabulário. A letra com maior entropia é a mais informativa, ajudando o jogador a tomar decisões mais precisas durante o jogo.

### Distribuição de Probabilidades
A distribuição de probabilidades modela a incerteza na taxa de acerto e erro do jogador automático. As simulações geraram uma curva normal, mostrando como os acertos e erros se distribuem, ajudando a entender o comportamento e a performance geral do modelo.

## Projeto
Este projeto implementa o jogo de forca com um jogador automático. A classe `JogoDeForca` simula o jogo de forca, permitindo que o jogador tente adivinhar a palavra através de tentativas de letras ou palavras completas. A classe `JogadorAutomatico` utiliza o vocabulário fornecido para calcular a entropia das letras e escolher as letras mais informativas para adivinhar a palavra.

### Funcionamento:
- O jogador automático escolhe letras com base na entropia, tentando otimizar suas chances de acerto.
- A cada tentativa de letra, o estado do jogo é atualizado, e o jogador ajusta as palavras possíveis com base nas informações obtidas.
- O jogo continua até o jogador errar todas as tentativas ou adivinhar corretamente a palavra.

## Conclusão
O projeto usa entropia e distribuição de probabilidades para otimizar um jogador automático no jogo de forca. 
As simulações mostraram que o jogador adivinhou a palavra corretamente em uma boa porcentagem de partidas, superando a estratégia de palpites aleatórios. 
Os resultados foram visualizados com gráficos de acertos/erros e uma curva de distribuição normal.


## Instruções de uso

1. Clone o repositório
2. Instale as dependências necessárias: `pip install -r requirements.txt`
3. Execute o notebook demo.ipynb para visualizar a demonstração completa.
