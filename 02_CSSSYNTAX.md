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

**CONTE??DOS DESSA SE????O**
1. A anatomia da Sintaxe CSS
2. Seletores de Classe (.)
3. Seletores de Id (#)
4. Pseudo-seletores
---

# 1. A Anatomia da Sintaxe CSS

Um c??digo CSS tem o seguinte visual.

## C??digo

```css
/*Coment??rios em verde.*/
/*A SINTAXE CSS*/

selector {property: value;}
```

- **SELECTOR**: ou "seletor", ?? **quem** voc?? quer mudar;
- **PROPERTY**: ou "propriedade", ?? **o que** voc?? quer mudar;
- **VALUE**: ou "valor", ?? **como** voc?? quer mudar aquela propriedade?

## Ordem alfab??tica

?? uma boa pr??tica alinhar as suas propriedades no arquivo CSS de acordo com ordem alfab??tica.


```css
/*ORDEM ALFAB??TICA*/

selector {
    a_property: value;
    b_property: value;
    c_property: value;
    d_property: value;
    }
```

---
# 2. Seletor de Classe (.)

O seletor de classe em uma tag HTML ajuda a gente a diferenciar uma tag espec??fica de outras. No HTML, voc?? adiciona ```class="alguma-coisa"```. No arquivo CSS, voc?? adiciona um ponto (.) ?? frente do nome da classe (no exemplo aqui, ?? o "alguma-coisa") para invocar o seltor dessa classe. Dessa forma, voc?? consegue diferenciar um grupo de tags HTML para que se comportem de determinada maneira: **?? uma identifica????o de grupo.**

Uma tag HTML pode ter v??rias classes diferentes. 

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

Assim como o anterior, o seletor de Id dentro de uma tag tamb??m ajuda a diferenciar uma tag particular de HTML das demais. Voc?? chama no arquivo CSS por uma hashtag. A diferen??a ?? que voc?? s?? pode identificar uma tag com um nome de Id espec??fico: **?? uma identifica????o ??nica** e n??o vai ser repetida. 

Uma tag HTML s?? pode ter um ??nico Id.

```css
#heading {
    font-color: blue;
}
```

---
# 4. Pseudo-classes (:)

?? uma palavra-chave adicionada para alguns seletores espec??ficos. Eles s??o adicionados com o s??mbolo ```:```, por exemplo, a pseudo-classe ```a:hover```.

Estas palavras-chave especificam um tipo especial de estado da tag HTML selecionada. A palavra-chave mais comum ?? "hover" - ele muda o estado da tag HTML quando voc?? passa o mouse sobre o componente. 

```css
button:hover {
    background-color: golden;
}
```

De uma maneira mais geral, a sintaxe disso t?? logo abaixo. N??o existem espa??os em branco entre o seletor e a pseudo-classe. ?? tudo junto mesmo.

```css
selector:pseudo-class {
    property: value;
}
```

