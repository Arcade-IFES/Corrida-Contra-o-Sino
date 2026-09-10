# Corrida Contra o Sino

Um jogo arcade em estilo retrô, desenvolvido em HTML, CSS e JavaScript, em que o jogador corre pelo pátio, evita obstáculos, coleta moedas e responde perguntas para abrir os portões até chegar ao sino final.

## Visão geral

O objetivo do jogo é atravessar as fases, avançando com velocidade e reflexo, sem perder as três vidas disponíveis. A cada fase, o jogador precisa alcançar um portão trancado por uma pergunta. Acertar a resposta pode dar bônus e aumentar a pontuação; errar ainda permite continuar, mas custa uma vida e reduz o ganho.

O jogo combina:

- corrida infinita / progressiva em cenário 2D
- pulos para desviar buracos e espinhos
- coleta de moedas para aumentar o combo
- perguntas de múltipla escolha em portões
- ranking local com nome do jogador
- visual arcade com HUD, telas e feedback retro

## Como jogar

1. Abra o arquivo index (neste projeto, o arquivo principal é o HTML do jogo) em um navegador moderno.
2. Clique em Jogar.
3. Use as setas esquerda e direita para se mover.
4. Use a barra de espaço para pular.
5. Evite buracos, espinhos e outros obstáculos.
6. Vá até o portão final da fase e responda corretamente para avançar.
7. Tente acumular o maior número de pontos possível antes de perder todas as vidas.

## Controles

- Setas esquerda e direita: movimentação
- Espaço: pulo
- P: pausar o jogo
- Botões na tela mobile: movimentação e pulo

## Mecânica do jogo

### Objetivo

- Percorrer o mapa até o sino final.
- Superar cada portão trancado com uma pergunta.
- Manter o máximo de vidas e pontos.

### Sistema de pontuação

- Pontos por progresso e conquistas.
- Moedas aumentam o combo.
- Acertos em perguntas podem gerar bônus maiores.
- Dano direto zera o combo atual.

### Vidas

- O jogador começa com 3 vidas.
- Buracos e espinhos provocam dano.
- Sem continues: a partida termina ao zerar as vidas.

### Ranking

O jogo salva um ranking local no navegador para registrar os melhores resultados. No rodapé do projeto há uma observação de que, para usar em rede escolar, as funções de ranking podem ser trocadas para persistência no servidor.

## Estrutura do projeto

- corrida-contra-o-sino.html: arquivo principal com toda a lógica, interface e estilo do jogo.
- readme.md: documentação do projeto.

## Como executar

Como o jogo é um projeto em HTML/JavaScript puro, basta abrir o arquivo principal em um navegador:

- Windows: clique duas vezes no arquivo HTML, ou
- use um servidor local simples, como:

  python -m http.server 8000

Depois acesse:

- http://localhost:8000/

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Canvas 2D
- LocalStorage para ranking local

## Observações

- O jogo foi pensado para funcionar em desktop e também em dispositivos móveis, com botões visuais para toque.
- As perguntas são de múltipla escolha e fazem parte do conteúdo educacional do jogo.
- O projeto pode ser expandido com mais fases, sons, animações e persistência em servidor.

## Possíveis melhorias futuras

- adicionar sons e música de fundo
- criar mais fases e níveis de dificuldade
- incluir sistema de energia, power-ups ou bônus especiais
- trocar o ranking local por banco de dados
- adicionar compatibilidade com mais idiomas

## Créditos

Este projeto foi desenvolvido como um jogo arcade de temática educativa e retrô, com foco em desafio, aprendizado e diversão.

---

Se quiser, posso também criar uma segunda versão do README com foco em:

- apresentação mais profissional para GitHub
- versão curta para divulgação
- README com badges, instruções de instalação e screenshots
- documentação técnica explicando a lógica do jogo em detalhes
