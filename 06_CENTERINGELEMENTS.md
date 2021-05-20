
# EN: Centering Elements in CSS

Let's imagine we have a bunch of elements in HTML and we want to center them all in the window. Like the Google Docs, we want to adjust the content to the center. How do we do that?

There are two ways: using the ```text-align``` property, or using the ```margin``` property.


PROPERTY | WIDTH | SHORTCUT
---------| ------| -----------
Text-Align | NO - No width set allowed  | Only works if we are dealing with an inline-block element or full width elements
Margin | YES - Allows width set | Use "auto" to do this


Let's check them out.

## 1. Text-align Property

The easiest way is to use the **text-align** property. 

But it has to be set in the **parent-element container**. Probably the body tag. 
```css
body {
    text-align: center;
}
```
This works if we are dealing with **inline-block elements or full width elements** (like the p tag). It works as long as the element **does not have a width set**.

## 2. Margin Property 

The other way is to work with **margins**.

```css
img {
    margin: 0 auto 0 auto;
}
```
This works **even if the element has a specific width set**. Use the "auto" to do this. Here's a shortcut.

```css
img {
    margin: 0 auto;
}
```


---
# PT: Centralizando Elementos em CSS

Vamos imaginar que temos um monte de elementos no nosso HTML e precisamos centralizá-los todos na janela. Assim como no Google Docs, quando estamos escrevendo o documento e queremos que ele seja todo centralizado ao meio. Como fazemos isso?

Tem dois jeitos: usando a propriedade ```text-align```, ou usando a propriedade ```margin```. 

PROPRIEDADE | LARGURA ('WIDTH') | ATALHO
------------| ----------------- | ---------
Text-Align | NÃO - não pode colocar uma width | Só funciona se tiver lidando com um elemento do tipo **inline-block** ou com elementos que ocupem toda a largura da janela
Margin | SIM - pode colocar uma width | Use o "auto" para fazer isso

Vamos olhar elas em detalhes.

## 1. Propriedade Text-Align

A maneira mais fácil... é usando essa propriedade.

Mas você vai ter que colocar ela **no container do elemento-pai**. Provavelmente vai ser a tag body.

```css
body {
    text-align: center;
}
```

Isso só funciona se você tiver lidando com **um elemento do tipo inline-block ou elementos que ocupem toda a largura (width)** (como a tag p, por exemplo). Só funciona se o elemento **não tiver uma width definida**. 

## 2. Propriedade Margin

O outro jeito é trabalhando com as **margins**. 

```css
img {
    margin: 0 auto 0 auto;
}
```
Isso funciona **até se o elemento tiver uma width definida**. Use o "auto" pra fazer isso. Aqui um atalho.

```css
img {
    margin: 0 auto;
}
```




