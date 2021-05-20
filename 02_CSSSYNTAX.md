# EN: About CSS

**CONTENTS OF THIS SECTION**
1. The Anatomy of the CSS Syntax
2. Class Selectors (.)
3. Id Selectors (#)
4. Pseudo Selectors

---

# 1. The Anatomy of the CSS Syntax

Here's what CSS code looks like.

## Code

```css
/*This is a comment in green*/
/*THE CSS SYNTAX*/

selector {property: value;}
```

- **SELECTOR**: **_who_** do you want to change?
- **PROPERTY**: **_what_** do you want to change in it?
- **VALUE**: **_how_** do you want to change that property?

## Alphabetical Order 

It is good practice to align your properties in **alphabetical order**.

```css
/*ALPHABETICAL ORDER*/

selector {
    a_property: value;
    b_property: value;
    c_property: value;
    d_property: value;
    }
```

---
# 2. Class Selectors (.)

A class selector inside a tag helps us differentiate a particular HTML tag. You have to add a dot to call the "class" selector. You can group different HTML tags to behave according to a class: **it is a group identification.**

Also, one HTML tag can have multiple classes.

```css
.bacon {
    background-color: green;
}

.broccoli {
    background-color: red;
}
```
---
# 3. Id Selectors (#)
Much like the previous one, the Id selector inside a tag also helps us differentiate one particular HTML tag. The difference, though, is that you can only identify ONE tag with the Id name: **it is a unique identification.**

Also, one HTML tag can have only one Id.

```css
#heading {
    font-color: blue;
}
```
---
# 4. Pseudo-classes (:)
It is a keyword added to specific selectors. They are added with the symbol ```:```, for example, ```a:hover``` pseudo-class.

These keywords specify a special state of the selected HTML tag. The most common keyword is the hover - it changes the state of the HTML tag whenever the mouse pointer hovers on top of it.

```css
button:hover {
    background-color: golden;
}
```
On a more general tone, this is the syntax below. There is no blank space in between selector and pseudo-class.

```css
selector:pseudo-class {
    property: value;
}
```

---
# PT: Sobre CSS

**CONTEÚDOS DESSA SEÇÃO**
1. A anatomia da Sintaxe CSS
2. Seletores de Classe (.)
3. Seletores de Id (#)
4. Pseudo-seletores
---

# 1. A Anatomia da Sintaxe CSS

Um código CSS tem o seguinte visual.

## Código

```css
/*Comentários em verde.*/
/*A SINTAXE CSS*/

selector {property: value;}
```

- **SELECTOR**: ou "seletor", é **quem** você quer mudar;
- **PROPERTY**: ou "propriedade", é **o que** você quer mudar;
- **VALUE**: ou "valor", é **como** você quer mudar aquela propriedade?

## Ordem alfabética

É uma boa prática alinhar as suas propriedades no arquivo CSS de acordo com ordem alfabética.


```css
/*ORDEM ALFABÉTICA*/

selector {
    a_property: value;
    b_property: value;
    c_property: value;
    d_property: value;
    }
```

---
# 2. Seletor de Classe (.)

O seletor de classe em uma tag HTML ajuda a gente a diferenciar uma tag específica de outras. No HTML, você adiciona ```class="alguma-coisa"```. No arquivo CSS, você adiciona um ponto (.) à frente do nome da classe (no exemplo aqui, é o "alguma-coisa") para invocar o seltor dessa classe. Dessa forma, você consegue diferenciar um grupo de tags HTML para que se comportem de determinada maneira: **é uma identificação de grupo.**

Uma tag HTML pode ter várias classes diferentes. 

```css
.bacon {
    background-color: green;
}

.broccoli {
    background-color: red;
}
```
---
# 3. Seletor de Id (#)

Assim como o anterior, o seletor de Id dentro de uma tag também ajuda a diferenciar uma tag particular de HTML das demais. Você chama no arquivo CSS por uma hashtag. A diferença é que você só pode identificar uma tag com um nome de Id específico: **é uma identificação única** e não vai ser repetida. 

Uma tag HTML só pode ter um único Id.

```css
#heading {
    font-color: blue;
}
```

---
# 4. Pseudo-classes (:)

É uma palavra-chave adicionada para alguns seletores específicos. Eles são adicionados com o símbolo ```:```, por exemplo, a pseudo-classe ```a:hover```.

Estas palavras-chave especificam um tipo especial de estado da tag HTML selecionada. A palavra-chave mais comum é "hover" - ele muda o estado da tag HTML quando você passa o mouse sobre o componente. 

```css
button:hover {
    background-color: golden;
}
```

De uma maneira mais geral, a sintaxe disso tá logo abaixo. Não existem espaços em branco entre o seletor e a pseudo-classe. É tudo junto mesmo.

```css
selector:pseudo-class {
    property: value;
}
```

