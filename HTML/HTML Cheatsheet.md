### Basic Tags

Creates an HTML document
```html
<html> </html>
```

Sets off the title & other info that isn't displayed
```html
<head> </head>
```

Sets off the visible portion of the document
```html
<body> </body>
```

Puts name of the document in the title bar; when bookmarking pages, this is what is bookmarked
Body attributes (only used in email newsletters)
```html
<title> </title>
```

<br>

### Body attributes (only used in email newsletters)
A hexadecimal color is specified with: #RRGGBB, where the RR (red), GG (green) and BB (blue) hexadecimal integers specify the components of the color.

Sets background color, using name or hex value
```html
<body bgcolor=?>
```

Sets text color, using name or hex value
```html
<body text=?>
```

Sets color of links, using name or hex value
```html
<body link=?>
```

Sets color of visited links, using name or hex value
```html
<body vlink=?>
```

Sets color of active links (while mouse-clicking)
```html
<body alink=?>
```

<br>

### Text Tags
Creates preformatted text
```html
<pre> </pre>
```

Creates headlines -- H1=largest, H6=smallest
```html
<h1> </h1> --> <h6> </h6>
```

Creates bold text (should use < "strong" > instead)
```html
<b> </b>
```

Creates italic text (should use < " em " "> instead)
```html
<i> </i>
```

Creates typewriter-style text
```html
<tt> </tt>
```

Used to define source code, usually monospace
```html
<code> </code>
```

Creates a citation, usually processed in italics
```html
<cite> </cite>
```

Creates address section, usually processed in italics
```html
<address> </address>
```

Emphasizes a word (usually processed in italics)
```html
<em> </em>
```

Emphasizes a word (usually processed in bold)
```html
<strong> </strong>
```

Sets size of font - 1 to 7 (should use CSS instead)
```html
<font size=?> </font>
```

Sets font color (should use CSS instead)
```html
<font color=?> </font>
```

Defines the font used (should use CSS instead)
```html
<font face=?> </font>
```

<br>

### Links

Creates a hyperlink to a Uniform Resource Locator
```html
<a href="URL">clickable text</a>
```

Creates a hyperlink to an email address
```html
<a href="mailto:EMAIL_ADDRESS">clickable text</a>
```

Creates a target location within a document
```html
<a name="NAME">
```

Creates a link to that target location
```html
<a href="#NAME">clickable text</a>
```

<br>

### Formatting

Creates a new paragraph
```html
<p> </p>
```

AInserts a line break (carriage return)
```html
<br>
```

Puts content in a quote - indents text from both sides
```html
<blockquote> </blockquote>
```

<div> </div>
Used to format block content with CSS
<span> </span>
Used to format inline content with CSS

### Lists
Creates an unordered list
```html
<ul> </ul>
```

Creates an ordered list (start=xx, where xx is a counting number)
```html
<ol start=?> </ol>
```

Encompasses each list item
```html
<li> </li>
```

Creates a definition list
```html
<dl> </dl>
```

Precedes each defintion term
```html
<dt>
```

Precedes each defintion 
```html
<dd>
```

<br>

### Graphical elements
Inserts a horizontal rule
```html
<hr>
```

Sets size (height) of horizontal rule
```html
<hr size=?>
```

Sets width of rule (as a % or absolute pixel length)
```html
<hr width=?>
```

Creates a horizontal rule without a shadow
```html
<hr noshade>
```



<img src="URL" />
Adds image; it is a separate file located at the URL
<img src="URL" align=?>
Aligns image left/right/center/bottom/top/middle (use CSS)
<img src="URL" border=?>
Sets size of border surrounding image (use CSS)
<img src="URL" height=?>
Sets height of image, in pixels
<img src="URL" width=?>
Sets width of image, in pixels
<img src="URL" alt=?>
Sets the alternate text for browsers that can't process images (required by the ADA)

<br>

### Forms

Defines a form
```html
<form> </form>
```

Creates a scrolling menu. Size sets the number of menu items visible before user needs to scroll.
```html
<select multiple name=? size=?> </select>
```

Creates a pulldown menu
```html
<select name=?> </select>
```

Sets off each menu item
```html
<option>
```

Creates a text box area. Columns set the width; Rows set the height.
```html
<textarea name=? cols="x" rows="y"></textarea>
```


Creates a checkbox.
```html
<input type="checkbox" name=? value=?>
```

Creates a checkbox which is pre-checked.
```html
<input type="checkbox" name=? value=? checked>
```

Creates a radio button.
```html
<input type="radio" name=? value=?>
```

Creates a radio button which is pre-checked.
```html
<input type="radio" name=? value=? checked>
```

Creates a one-line text area. Size sets length, in characters.
```html
<input type="text" name=? size=?>
```

Creates a submit button. Value sets the text in the submit button.
```html
<input type="submit" value=?>
```

Creates a submit button using an image.
```html
<input type="image" name=? src=? border=? alt=?>
```

Creates a reset button
```html 
<input type="reset">
```

<br>

### Tables (use only for data layout - use CSS for page layout)

Creates a table
```html
<table> </table>
```

Sets off each row in a table
```html
<tr> </tr>
```

Sets off each cell in a row
```html
<td> </td>
```

Sets off the table header (a normal cell with bold, centered text)

```html
<th> </th>
```

<br>

### HTML5 input tag attributes 
Not all browsers support; visit http://caniuse.com for details

Sets a single-line textbox for email addresses
```html
<input type="email" name=?>
```

Sets a single-line textbox for URLs
```html
<input type="url" name=?>
```

Sets a single-line textbox for a number
```html
<input type="number" name=?>
```

Sets a single-line text box for a range of numbers
```html
<input type="range" name=?>
```

Sets a single-line text box with a calendar showing the date/month/week/time
```html
<input type="date/month/week/time" name=?>
```

Sets a single-line text box for searching
```html
<input type="search" name=?>
```

Sets a single-line text box for picking a color
```html
<input type="color" name=?>
```


### Table attributes (only use for email newsletters)

Sets the width of the border around table cells
```html
<table border=?>
```

Sets amount of space between table cells
```html
<table cellspacing=?>
```

Sets amount of space between a cell's border and its contents
```html
<table cellpadding=?>
```

Sets width of the table in pixels or as a percentage
```html
<table width=?>
```

Sets alignment for cells within the row (left/center/right)
```html
<tr align=?>
```

Sets alignment for cells (left/center/right)
```html
<td align=?>
```

Sets vertical alignment for cells within the row (top/middle/bottom)
```html
<tr valign=?>
```

Sets vertical alignment for cell (top/middle/bottom)
```html
<td valign=?>
```

Sets number of rows a cell should span (default=1)
```html
<td rowspan=?>
```

Sets number of columns a cell should span
```html
<td colspan=?>
```

Prevents lines within a cell from being broken to fit
```html
<td nowrap>
```

