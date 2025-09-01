Esse foi um projeto que fiz recentemente utilizando Html, css e Javascript.
Utilizei vários vídeos, materiais e conteúdos de apoio para a realização desse projeto. Minha maior base para o projeto foi este vídeo https://youtu.be/FbpwGnKSkJU?si=YgIfieN4sIlSqPMt.
Fiz algumas alterações no projeto, como:

HTML

Criei um div.display com duas partes:

.expression → visor pequeno para a operação (ex.: 12 + 7)

.result → continua sendo o visor principal

CSS

Adicionei .display para agrupar os visores.

.expression ficou menor e em cinza claro.

.result continua grande, mas agora separado embaixo.

JavaScript

Adicionei a função updateExpression() para montar a string da operação e exibir no visor.

Passei a chamá-la junto de updateResult() sempre que algo muda.

Resultado:

Um visor de expressão e outro visor de resultado. Assim, o usuário sempre vê o cálculo em andamento.
