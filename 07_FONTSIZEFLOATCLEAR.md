# EN: The Font Size

These are the standard specifications for font size:

```css
16px = 100% = 1em
```
Pixels are static. 

Percentages and Ems are not - they inherit from parent-elements.

But there's also Rem.

Rem does not inherit from parent-elements, it generates size according to the root. That's why the R in front of 'em' - it means 'root'.

# Float and Clear (wrap around or not wrap around)

**FLOAT** is a property. 

**The float property makes your text wrap around an image, instead of acting like a block below it**. So, you can have an image and a text right beside it.

**WATCH OUT: DO NOT USE IT FOR POSITIONING - JUST FOR TEXT WRAPPING AROUND IMAGES.**

Seriously, don't do this.

```css
.img {
    float: left;
}
```

**CLEAR** is also a property.

It prevents the element from wrapping anything beside it. You **cannot wrap beside it.**

Think of it as the "anti-float": it takes off the text wrapping around an image and make it act like a block below it.

---
# PT: Tamanho da Fonte

Essas são as especificações padrões para o tamanho da fonte:

```css
16px = 100% = 1em
```

Pixels são estáticos.

Porcentagens e Ems não são estáticos - eles herdam do elemento-pai.

Mas tem também o Rem.

Rem não herda do elemento-pai, ele gera um tamanho de acordo com a raiz. É por isso que tem o R na frente de 'em' - significa 'raiz'.

# Float e Clear (embrulhar em volta do objeto ou não embrulhar em volta do objeto)

**FLOAT** é uma propriedade.

**A propriedade float faz com que o seu texto se embrulhe ao redor de uma imagem, em vez de agir como se fosse um bloco embaixo dela**. Assim, você consegue ter uma imagem e um texto logo ao lado da imagem.

**CUIDADO: NÃO USE O FLOAT PARA POSICIONAR - SÓ PARA EMBRULHAR O TEXTO EM VOLTA DE IMAGENS.**

Sério, faz isso não.


```css
.img {
    float: left;
}
```

**CLEAR** também é uma propriedade. 

Ela previne que o elemento permita que algo se embrulhe perto dele. Você **simplesmente não consegue embrulhar nada ao lado/em volta do elemento.**

Pensa como se fosse um "anti-float": faz com que um texto pare de agir como um embrulho do lado da imagem, e faz com que esse texto haja como um bloco puro embaixo da imagem (e não do lado).
