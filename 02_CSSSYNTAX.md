# About CSS

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