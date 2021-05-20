# EN: The CSS Display Property

This section is about **how the elements will be displayed on the page taking into consideration the box model concept**.

There are four types of display.

1. **Block**
2. **Inline**
3. **Inline-block**
4. **None**

I created this so it helps me.

*PS: Horizon bench is what I call an imaginary "box" that occupies the whole width of a single line. Sometimes one element will occupy this box alone (it sits alone) and other times more elements can share the space of this horizontal box.*

Maybe it'll help you.

TYPE OF DISPLAY | WIDTH | HORIZON BENCH 
:----------------|:-------|:-----------------
BLOCK | You can change it | It sits alone
INLINE | Nope, can't change it | It sits with friends
INLINE-BLOCK | You can change it | It sits with friends
NONE | It's gone | It's gone


Let's view them in details.

---

## 1. Block
By default, some elements are block display. This means they occupy the whole width of the page. No other element can sit with them in the same "bench" - they occupy it all.

You **can change the width** of these elements, but still **does not let** another element **sit on the bench** with them.

- paragraphs (p)
- headers (h1, h2, h3, h4, h5, h6)
- divisions (div)
- lists and list items (ol, ul, li)
- forms (form)

## 2. Inline
By default, these elements only occupy their own selves. This means other elements can sit with them in the same "bench" - they only ocuppy their own little space.

You **can't change the width** of these elements, though.

If you try, it does nothing.

- spans (span)
- images (img)
- anchors (a)

## 3. Inline-block
The best of both worlds.
 
You **can change the width** AND it still **lets other elements sit on the bench** with them.

## 4. None

It gets rid of our element.

*Hint: there's also a property called visibility. It maintains the elements' space but it turns it invisible.*

---
# PT: A Propriedade CSS Display

Essa parte tem a ver em **como os elementos vão se apresentar na tela, levando em consideração o Modelo de Caixa**.

São quatro tipos de display (modo de aparecer na tela).

1. **Block**
2. **Inline**
3. **Inline-block**
4. **None**

Vamos ver cada um em detalhes.

*PS: Eu chamo de "banco do horizonte", uma caixa retangular imaginária de altura 1 linha e largura de toda a página. Às vezes apenas um elemento pode sentar nesse banco. Outras vezes, vários elementos podem dividir esse banco e ocupar o mesmo horizonte. Cada linha, em tese, é feita por uma caixa dessa (um banco do horizonte)... já que tratamos de um modelo de caixa aqui.*

TIPO DE DISPLAY | LARGURA (WIDTH) | BANCO DO HORIZONTE
:----------------|:-------|:-----------------
BLOCK | Você consegue mudar | Senta sozinho
INLINE | Não, não dá pra mudar | Pode sentar com amigos
INLINE-BLOCK | Você consegue mudar | Pode sentar com amigos
NONE | Foi embora | Nem tá mais aqui

---

## 1. Block

Por padrão, alguns elementos são do tipo "block display" - são mostrados na tela em formato de bloco. Isso significa que eles ocupam toda a largura da página. Nenhum outro elemento pode sentar com eles nesse "banco" retangular - eles ocupam tudo. 

Você **pode mudar a largura** desses elementos, mas isso ainda **não permite que outros elementos fiquem com eles no "banco"**, só eles ocupam esse horizonte.

Alguns exemplos.

- paragraphs (p)
- headers (h1, h2, h3, h4, h5, h6)
- divisions (div)
- lists and list items (ol, ul, li)
- forms (form)


## 2. Inline

Por padrão, esses elementos apenas ocupam a si mesmo. Isso significa que outros elementos podem sentar com eles no "banco" retangular que ocupa toda a largura de uma página - eçes apenas ocupam seu próprio espaço, outros podem ocupar o horizonte junto com eles.

Você **não pode mudar a largura (width)** desses elementos. 

Mesmo que você tente, nada acontece. 

Alguns exemplos de elementos abaixo.

- spans (span)
- images (img)
- anchors (a)


## 3. Inline-block

O melhor dos dois mundos!

Você **pode mudar a largura (width)** E ELE AINDA **deixa os outros elementos sentarem com ele no banco do horizonte**. Eles não ocupam um horizonte sozinho. 

## 4. None

Some com o nosso elemento. 

*Dica: também tem uma propriedade chamada visibility. Ele mantém o espaço que seria ocupado pelos elementos mas torna os elementos invisíveis.*