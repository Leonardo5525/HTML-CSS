Com certeza! Aqui está a transcrição do conteúdo da imagem "CSS Cheat Sheet" em markdown:

# CSS Cheat Sheet

## Selector

### Basic Selectors

- **Universal selector:** `*` 
- **Element Selector:** `element` - seleciona todos os elementos com o nome especificado
	- `element, element` - seleciona todos os elementos que correspondem a qualquer um dos seletores
	- `element > element` - seleciona os elementos que são filhos diretos do elemento pai especificado
	- `element + element` - seleciona o elemento irmão adjacente ao elemento especificado
	-  `element.class` - seleciona todos os elementos com o nome especificado e a classe especificada
- **Class Selector:** `.class ` - seleciona todos os elementos com a classe especificada
- **ID Selector:** `#id`
	 Selects elements based on their ID attribute, using a hash (`#`) before the ID name.

  ```css
  #my-id {
    /* CSS Rules Here */
  }
  ```

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

- **Attribute Selector:** Selects elements based on their attribute values, using brackets and an optional attribute operator.

  ```css
  [type="text"] {
    /* CSS Rules Here */
  }
  ```
<br>

### Combinators

- **Descendant combinator:** `ancestor descendant`
- **Child combinator:** `parent > child`
- **Adjacent sibling combinator:** `element + sibling`
- **General sibling combinator:** `element ~ sibling`

### Attribute Selectors

- **Presence Selector:** `[attribute]`
- **Exact value Selector:** `[attribute="value"]`
- **Attribute starting with Selector:** `[attribute^="value"]`
- **Attribute ending with Selector:** `[attribute$="value"]`
- **Attribute containing Selector:** `[attribute*="value"]`
<br>

## Style

### Background
Define the color of the background in the element.
Sets the background image, color, and position of an element.
```css
background-image: url("image.jpg");
background-color: blue;
background-position: center center;
```

- `background-color` - used to specify the background color of an element.
- `background-image` - used to add one or more background images to an element.
- `background-repeat` - used to add or remove repeat the background image both horizontally and vertically.
- `background-position` - used to specify the positioning of the image in a certain way.
- `background-attachment` -used to specify the kind of attachment of the background image with respect to its container.
- `background-size` - sets the size of the element's background image. The image can be left to its natural size, stretched, or constrained to fit the available space.
- `background-clip` - used to define how far the background (color or image) should extend within an element.
- `background-origin` - used to adjust the background image of the webpage.

### Border

- `border` - sets the width, style, and color of an element's border.
  ```css
  border: 1px solid black;
  border-radius: 5px;
  ```

- `border-color`
- `border-style`
- `border-width`
- `border-radius`
- `border-collapse`

### Text

- `color` - defining the text color
 Sets the color of an element's text or background.
  ```css
  color: red;
  background-color: yellow;
  ```
 
- `font` - sets the font family, size, weight, and style of an element's text.
  ```css
  font-family: Arial, sans-serif;
  font-size: 16px;
  font-weight: bold;
  font-style: italic;
  ```

- `font-family` - define the family font of the text
- `font-size` - define the size font of the text
- `font-style` - define the style font of the text (normal, italic, oblique)
	- *oblique*: is a sloped version of the regular face.
- `font-weight` - define the thickness font of the text (normal, bold, strong)
- `text-align`
- `text-decoration`
- `text-transform`
- `line-height`

### Box Model
Sets the width, height, and content area of an element.
  ```css
  width: 300px;
  height: 200px;
  box-sizing: border-box;
  ```

- `width` - define the width of a element
- `height` - define the height of a element
- `margin` - define the externals margins of a element
- `padding` - define the inner padding of a element
	 **Margin and Padding:** Sets the amount of space between an element's content and its border, or between an element's border and other elements.
  ```css
  margin: 10px;
  padding: 20px;
  ```

- `box-sizing` - define the border of a element

### Positioning

- `position` - define the type of positioning in a element (static, relative, absolute, fixed). Sets the position and z-index of an element:
  ```css
  position: relative;
  top: 10px;
  left: 20px;
  z-index: 1;
  ```

 Define the positioning of a element in relation to the border of the main element:
	- `top`
	- `right`
	- `bottom`
	- `left`
- `z-index`

### Display

- `display` - define the family font of the text. Sets how an element is displayed on the page.
  ```css
  display: block;
  display: inline-block;
  display: flex;
  ```

- `visibility`
- `opacity` - define the opacity of the element (0 to 1)

## Values

- **Length Units:** `px`, `em`, `rem`, `%`
- **Color Values:** `name`, `hex`, `rgb`, `rgba`
- **Position Values:** `top`, `right`, `bottom`, `left`, `center`
- **Font Values:** `family-name`, `generic-name`, `bold`, `italic`
- **List Values:** `unordered`, `ordered`, `none`

### Animation
- **Transition:** Sets the duration, timing function, and properties to animate when a change occurs.

  ```css
  transition: 1s ease-in-out;
  transition-property: background-color, color;
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
```css
div::before {
  /* CSS Rules Here */
}
```


## Resources

- [CSS-Tricks](https://css-tricks.com/)
- [MDN Web Docs CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)