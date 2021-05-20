
# EN: CSS Positions

Your HTML content already comes with a default positioning for each element.

We're gonna see how to change that here.

But first, let's remember the rules.

# Rules to the Game

1. **CONTENT IS EVERYTHING**

The height is defined by the size of the content and the width is not. So, essencially, the size of your box will be generated from its content.

2. **ORDER COMES FROM CODE**

 Title first, paragraph then, image last? You decide.

3. **CHILDREN SIT ON PARENTS**

 There's a z-axis. This is relative from the screen to the user point of view. It's about what's stacked on top of what. 

4. **POSITION**

There are four types of positioning. They are *STATIC, RELATIVE, ABSOLUTE, FIXED*.

# The Positions Table

Here's a table that might help you remember the tricks.

POSITION | MEANING
---------|--------
STATIC | Default to HTML
RELATIVE | Relative to what it should be positioned if it were static (HTML-default).
ABSOLUTE | Relative to the parent-element (in most cases, the body). This way, all other elements change positions because... the element you're moving, scrolls out of the flow of the default-elements. This is great to **create a parent element and move it... moving also the child-elements according to parent-element**.
FIXED | The element is fixed on the screen. If you scroll down, it will move along with you.

---
# PT: CSS Posições

Seu conteúdo em HTML já vem com uma posição padronizada para cada elemento.

A gente vai ver como mudar isso aqui.

Mas primeiro, vamos lembrar as regras.

# Regras do Jogo

1. **CONTEÚDO É TUDO**

A altura é definida pelo tamanho do conteúdo e a largura não. Então, na realidade, a altura da sua caixa vai ser gerada pelo seu conteúdo.

2. **A ORDEM É DITA PELO CÓDIGO**

Primeiro o título, depois o parágrafo, depois... a imagem por último? É você que decide no código.

3. **FILHOS SENTAM NOS PAIS**

Existe um eixo-Z. Este eixo é relativo da tela do computador até o usuário. É profundidade. E trata sobre como as coisas estão empilhadas nessa profundidade abstrata. 

4. **POSIÇÕES**

Existem quatro tipos de posicionamentos. Eles são: *STATIC, RELATIVE, ABSOLUTE, FIXED.*

# A Tabela das Posições

Essa é uma tabela que pode ajudar a se lembrar dos truquinhos básicos com CSS.

POSIÇÕES | SIGNIFICADO
---------| ------------
STATIC | É a posição padrão do HTML
RELATIVE | É a posição relativa à posição de "como deveria ser" se fosse estático (padrão HTML)
ABSOLUTE | É relativo ao elemento-pai (na maior parte dos casos, é o body). Assim, todos os elementos mudam de posições porque... o elemento que você tá movendo, se move por cima dos elementos padrões. E isso é ótimo para **criat um elemento-pai e depois movê-lo... assim, todos os elementos-filhos também se movem de acordo com esse elemento-pai**. 
FIXED | O elemento é fixado na tela. Se você move a página pra baixo, ele vai mover junto com a sua navegação.
