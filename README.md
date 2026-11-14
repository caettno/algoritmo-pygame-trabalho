# Professor.exe

Projeto final da disciplina de Introdução a Algoritmos/Programação, desenvolvido com Python e Pygame.

Este repositório é um template para os grupos da disciplina. A proposta é começar com uma base funcional e evoluir o jogo ao longo do semestre.

## Integrantes do grupo

- Igor Caetano Tibério Figueiredo
- Brendon Leonardo Martins Alves
- Danilo Amaral Nadu
- Brendon Leonardo Martins Alves

## Estrutura do projeto

- `main.py`: ponto de entrada da aplicação.
- `src/`: código-fonte principal do jogo (loop, regras, sprites e dados).
- `assets/`: imagens, fontes e sons.
- `data/`: arquivos persistentes (recorde/ranking).
- `tests/`: testes unitários com `pytest`.
- `docs/`: documentação do projeto, incluindo proposta inicial.

## Descrição do jogo

O Professor.exe é um jogo de investigação e tomada de decisões, no qual o jogador assume o papel de um professor responsável por corrigir avaliações escolares e identificar possíveis usos indevidos de inteligência artificial.

Exemplo:

Durante a correção, o jogador deverá analisar as respostas dos alunos, identificar inconsistências e consultar um detector de IA que nem sempre apresenta resultados corretos. Conforme o jogo avança, as avaliações se tornam mais complexas, exigindo maior atenção e pensamento crítico.

## Objetivo do jogador

O objetivo é corrigir as avaliações de maneira justa, identificando possíveis irregularidades sem acusar injustamente os alunos.

O jogador deverá analisar as respostas, consultar evidências e decidir se uma avaliação deve ser aceita ou encaminhada para investigação. Para avançar, será necessário manter uma boa reputação e atingir a pontuação mínima de cada fase.
Exemplo:

## Regras do jogo

- O jogador recebe avaliações contendo perguntas e respostas de diferentes alunos.
- Cada avaliação poderá apresentar inconsistências, informações incorretas ou indícios de uso indevido de IA.
- O jogador poderá consultar um detector de inteligência artificial, mas suas recomendações nem sempre serão confiáveis.
- O jogador poderá investigar evidências adicionais antes de tomar uma decisão.
- Cada decisão correta aumenta a pontuação.
- Acusar injustamente um aluno ou ignorar irregularidades comprovadas reduz a pontuação e a reputação.
- O jogador terá uma quantidade limitada de recursos para investigar as avaliações.
- O jogo será dividido em dias de trabalho, com dificuldade progressiva.
- Para avançar, o jogador deverá atingir a pontuação mínima e manter sua reputação acima do limite estabelecido.
- A partida termina quando o jogador conclui todos os dias de trabalho ou perde toda a sua reputação.

## Controles

Informe as teclas ou comandos utilizados no jogo.

Exemplo:

- Mouse: selecionar avaliações, botões e opções disponíveis.
- Botão esquerdo do mouse: abrir provas, consultar o detector de IA e investigar evidências.
- Botão "Aceitar": aprovar a avaliação.
- Botão "Investigar": encaminhar a avaliação para uma análise adicional.
- Botão "Próxima prova": avançar para a próxima avaliação após registrar uma decisão.
- ESC: pausar o jogo ou acessar o menu.

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone LINK_DO_REPOSITORIO
cd NOME_DA_PASTA
pip install -r requirements.txt
python main.py
```

## Como executar os testes

```bash
python -m pytest
```

## Checklist mínimo para entrega

- Preencher este README com nome final, descrição real, regras e controles do jogo.
- Atualizar `docs/proposta.MD` com a proposta do grupo.
- Garantir que o jogo executa com `python main.py`.
- Garantir que os testes passam com `pytest`.

## Observações para os alunos

- Mantenham o código organizado em módulos pequenos e com responsabilidade clara.
- Comentem partes importantes da lógica, principalmente regras do jogo.
- Registrem decisões técnicas no README do grupo ao longo do desenvolvimento.
