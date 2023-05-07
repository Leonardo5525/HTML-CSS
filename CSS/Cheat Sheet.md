# Backgrounds
## Backgrounds
[[#background-image]]
[[#background-position]]
[[#background-size]]
[[#background-repeat]]
[[#background-attachment]]
[[#background-origin]]
[[#background-clip]]
[[#background-color]]

# [[#Border]]
[[#border-width]]
[[#border-style]]
[[#border-color]]
## [[#border-left]]
[[#border-left-width]]
[[#border-left-style]]
[[#border-left-color]]
## [[#border-right]]
[[#border-right-width]]
[[#border-right-style]]
[[#border-right-color]]
## [[#border-top]]
[[#border-top-width]]
[[#border-top-style]]
[[#border-top-color]]
## [[#border-bottom]]
[[#border-bottom-width]]
[[#border-bottom-style]]
[[#border-bottom-color]]

### background-image
url
gradients
none

### background-position
top left | top center | top right | center left | center center |
center right | bottom left | bottom center | bottom right
x-% y-%
x-pos y-pos

### background-size
length
%
auto | cover | contain

### background-repeat
repeat | repeat-x | repeat-y |
no-repeat

### background-attachment
scroll | fixed | local

### background-origin
border-box | padding-box | content-box

### background-clip
border-box | padding-box | content-box

### background-color
color
transparent
<br>

# Border

### border-width
thin | medium | thick | length

### border-style
none | hidden | dotted |
dashed | solid | double |
groove | ridge | inset | outset

### border-color
color

## border-left

### border-left-width
thin | medium | thick length

### border-left-style
border-style

### border-left-color
border-color

## border-right

### border-right-width
thin | medium | thick | length

### border-right-style
border-style

### border-right-color
border-color

## border-top

### border-top-width
thin | medium | thick | length

### border-top-style
border-style

### border-top-color
border-color


## border-bottom

### border-bottom-width
thin | medium | thick | length

### border-bottom-style
border-style

### border-bottom-color
border-color

<br>

# Box Model

### float
left | right | none

### height
auto
length
%

### max-height
none
length
%

### max-width
none
length%

### min-height
none
length
%

### width
auto
%
length

### margin
margin-top
margin-right
margin-bottom
margin-left
margin-bottom


# CSS Cheat Sheet

## Seletores

-   `element` - seleciona todos os elementos com o nome especificado
-   `.class` - seleciona todos os elementos com a classe especificada
-   `#id` - seleciona o elemento com o ID especificado
-   `element, element` - seleciona todos os elementos que correspondem a qualquer um dos seletores
-   `element.class` - seleciona todos os elementos com o nome especificado e a classe especificada
-   `element > element` - seleciona os elementos que são filhos diretos do elemento pai especificado
-   `element + element` - seleciona o elemento irmão adjacente ao elemento especificado

## Propriedades

### Cores

-   `color` - define a cor do texto
-   `background-color` - define a cor de fundo de um elemento
-   `opacity` - define a opacidade de um elemento (0 a 1)

### Texto

-   `font-family` - define a família de fontes para o texto
-   `font-size` - define o tamanho da fonte para o texto
-   `font-style` - define o estilo da fonte (normal, itálico, obliqua)
-   `font-weight` - define a espessura da fonte (normal, negrito, mais pesado)

### Layout

-   `display` - define como um elemento deve ser exibido (block, inline, none)
-   `width` - define a largura de um elemento
-   `height` - define a altura de um elemento
-   `margin` - define as margens externas de um elemento
-   `padding` - define o preenchimento interno de um elemento
-   `border` - define a borda de um elemento

### Posicionamento

-   `position` - define o tipo de posicionamento de um elemento (static, relative, absolute, fixed)
-   `top`, `bottom`, `left`, `right` - define a posição de um elemento em relação à borda do elemento pai.

Sure, here's a CSS cheat sheet in Markdown:


Sure, here's a CSS cheat sheet written in Markdown:

## CSS Cheat Sheet

### Selector Types

- **Type Selector:** Selects elements based on their tag name, such as `div` or `p`.

  ```css
  div {
    /* CSS Rules Here */
  }
  ```

- **Class Selector:** Selects elements based on their class attribute, using a period (`.`) before the class name.

  ```css
  .my-class {
    /* CSS Rules Here */
  }
  ```

- **ID Selector:** Selects elements based on their ID attribute, using a hash (`#`) before the ID name.

  ```css
  #my-id {
    /* CSS Rules Here */
  }
  ```

- **Attribute Selector:** Selects elements based on their attribute values, using brackets and an optional attribute operator.

  ```css
  [type="text"] {
    /* CSS Rules Here */
  }
  ```

### CSS Properties

- **Color:** Sets the color of an element's text or background.

  ```css
  color: red;
  background-color: yellow;
  ```

- **Font:** Sets the font family, size, weight, and style of an element's text.

  ```css
  font-family: Arial, sans-serif;
  font-size: 16px;
  font-weight: bold;
  font-style: italic;
  ```

- **Margin and Padding:** Sets the amount of space between an element's content and its border, or between an element's border and other elements.

  ```css
  margin: 10px;
  padding: 20px;
  ```

- **Border:** Sets the width, style, and color of an element's border.

  ```css
  border: 1px solid black;
  border-radius: 5px;
  ```

- **Background:** Sets the background image, color, and position of an element.

  ```css
  background-image: url("image.jpg");
  background-color: blue;
  background-position: center center;
  ```

- **Display:** Sets how an element is displayed on the page.

  ```css
  display: block;
  display: inline-block;
  display: flex;
  ```

- **Position:** Sets the position and z-index of an element.

  ```css
  position: relative;
  top: 10px;
  left: 20px;
  z-index: 1;
  ```

- **Transition:** Sets the duration, timing function, and properties to animate when a change occurs.

  ```css
  transition: 1s ease-in-out;
  transition-property: background-color, color;
  ```

- **Box Model:** Sets the width, height, and content area of an element.

  ```css
  width: 300px;
  height: 200px;
  box-sizing: border-box;
  ```

### Units of Measurement

- **Pixels (px):** Sets an absolute length, based on screen pixels.

- **Percent (%):** Sets a length relative to the parent element's size.

- **Viewport Units (vw, vh):** Sets a length relative to the size of the viewport.

- **Em and Rem:** Sets a length relative to the font size of the current or root element.

### Pseudo-Classes and Pseudo-Elements

- **Pseudo-Classes:** Selects elements based on their state or position, such as `:hover` or `:nth-child`.

  ```css
  a:hover {
    /* CSS Rules Here */
  }
  ```

- **Pseudo-Elements:** Inserts content before or after an element, such as `::before` or

# CSS Cheat Sheet

## Selector Types

- **Type Selector:** Selects elements based on their tag name, such as `div` or `p`.

```css
div {
  /* CSS Rules Here */
}
```

- **Class Selector:** Selects elements based on their class attribute, using a period (`.`) before the class name.

```css
.my-class {
  /* CSS Rules Here */
}
```

- **ID Selector:** Selects elements based on their ID attribute, using a hash (`#`) before the ID name.

```css
#my-id {
  /* CSS Rules Here */
}
```

- **Attribute Selector:** Selects elements based on their attribute values, using brackets and an optional attribute operator.

```css
[type="text"] {
  /* CSS Rules Here */
}
```

## CSS Properties

- **Color:** Sets the color of an element's text or background.

```css
color: red;
background-color: yellow;
```

- **Font:** Sets the font family, size, weight, and style of an element's text.

```css
font-family: Arial, sans-serif;
font-size: 16px;
font-weight: bold;
font-style: italic;
```

- **Margin and Padding:** Sets the amount of space between an element's content and its border, or between an element's border and other elements.

```css
margin: 10px;
padding: 20px;
```

- **Border:** Sets the width, style, and color of an element's border.

```css
border: 1px solid black;
border-radius: 5px;
```

- **Background:** Sets the background image, color, and position of an element.

```css
background-image: url("image.jpg");
background-color: blue;
background-position: center center;
```

- **Display:** Sets how an element is displayed on the page.

```css
display: block;
display: inline-block;
display: flex;
```

- **Position:** Sets the position and z-index of an element.

```css
position: relative;
top: 10px;
left: 20px;
z-index: 1;
```

- **Transition:** Sets the duration, timing function, and properties to animate when a change occurs.

```css
transition: 1s ease-in-out;
transition-property: background-color, color;
```

- **Box Model:** Sets the width, height, and content area of an element.

```css
width: 300px;
height: 200px;
box-sizing: border-box;
```

## Units of Measurement

- **Pixels (px):** Sets an absolute length, based on screen pixels.

- **Percent (%):** Sets a length relative to the parent element's size.

- **Viewport Units (vw, vh):** Sets a length relative to the size of the viewport.

- **Em and Rem:** Sets a length relative to the font size of the current or root element.

## Pseudo-Classes and Pseudo-Elements

- **Pseudo-Classes:** Selects elements based on their state or position, such as `:hover` or `:nth-child`.

```css
a:hover {
  /* CSS Rules Here */
}
```

- **Pseudo-Elements:** Inserts content before or after an element, such as `::before` or `::after`.

```css
div::before {
  /* CSS Rules Here */
}
```
