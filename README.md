### LINK PARA O SITE DA CALCULADORA WEB: https://gabriel-d-anjos.github.io/Calculadora-Web/
----------------------------------------------------------------------------------------


### Descrição do projeto:

Esse foi um projeto que fiz recentemente utilizando HTML, CSS e JavaScript.
Utilizei vários vídeos, materiais e conteúdos de apoio para a realização desse projeto. Minha maior base para o projeto foi este vídeo https://youtu.be/FbpwGnKSkJU?si=YgIfieN4sIlSqPMt.

Fiz algumas alterações no projeto, como:

### HTML

Criei um div.display com duas partes:

.expression → visor pequeno para a operação (ex.: 12 + 7)

.result → continua sendo o visor principal
----------------------------------------------------------------------------------------
### CSS

Adicionei .display para agrupar os visores.

.expression ficou menor e em cinza claro.

.result continua grande, mas agora separado embaixo.
----------------------------------------------------------------------------------------
### JavaScript

Adicionei a função updateExpression() para montar a string da operação e exibir no visor.

Passei a chamá-la junto de updateResult() sempre que algo muda.
----------------------------------------------------------------------------------------
**`Resultado`**:

Um visor de expressão e outro visor de resultado. Assim, o usuário sempre vê o cálculo em andamento.

----------------------------------------------------------------------------------------
### O que eu aprendi fazendo a calculadora:

### HTML

Estruturar um projeto web simples com <!DOCTYPE html>, <head> e <body>.

Criar botões (<button>) para cada ação e organizar em um grid.

Usar divs específicas para separar áreas (visor, botões, expressão).

----------------------------------------------------------------------------------------

### CSS

Usar Flexbox para centralizar a calculadora na tela.

Criar um grid de botões com grid-template-columns: repeat(4, 1fr);.

Diferenciar estilos com classes reutilizáveis (bg-gray, bg-orange, button-zero).

Aplicar cores e hierarquia visual (resultado grande, expressão menor).

Criar uma interface parecida com calculadoras reais (estilo clean e responsivo).

----------------------------------------------------------------------------------------

### JavaScript

Selecionar elementos (querySelector, querySelectorAll).

Adicionar eventos nos botões com forEach.

Manipular dados (strings e números, trocar . por ,).

Controlar o estado do cálculo com variáveis (currentNumber, firstOperand, operator, restart).

Funções principais:

addDigit() → adiciona números.

setOperator() → guarda o operador.

calculate() → faz a conta.

clearCalculator() → limpa tudo.

setPercentage() → calcula porcentagem.

updateResult() → atualiza o visor.

updateExpression() → mostra a conta em andamento.

Tratar casos especiais:

Evitar vírgulas duplicadas.

Limitar casas decimais.

Inverter sinal (±).

Separar visores: um para a operação em andamento e outro para o resultado final.

----------------------------------------------------------------------------------------

*nota

caso tenha alguma sugestão/ideia sobre o que posso melhorar fico a disposição para receber feedbacks.
