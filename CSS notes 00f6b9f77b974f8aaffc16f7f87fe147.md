# CSS notes

# CSS color

how to change color of html elements

```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```

# CSS backgrounds

how to change CSS backgrounds

```html
background-color:
body {
  background-color: lightblue;
}
background-image:url("paper.gif");
background-position:
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
}

```

# CSS syntax

```html
<h1 style="color:blue;">A Blue Heading</h1> inline
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head> internal
<head>
  <link rel="stylesheet" href="styles.css">
</head>
external
```

# CSS margins

Margins are used to create space around elements, outside of any defined borders.

```html
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
p {
  margin: 25px 50px 75px 100px;
}
top margin is 25px
right margin is 50px
bottom margin is 75px
left margin is 100px
```

# CSS padding

Padding is used to create space around an element's content, inside of any defined borders.

```html
div {
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
}
div {
  padding: 25px 50px 75px 100px;
}
top padding is 25px
right padding is 50px
bottom padding is 75px
left padding is 100px
```

# CSS borders

The CSS border properties allow you to specify the style, width, and color of an element's border.

```html
dotted - Defines a dotted border, dashed - Defines a dashed border, solid - Defines a solid border, double - Defines a double border
groove - Defines a 3D grooved border. The effect depends on the border-color value
ridge - Defines a 3D ridged border. The effect depends on the border-color value
inset - Defines a 3D inset border. The effect depends on the border-color value
outset - Defines a 3D outset border. The effect depends on the border-color value
none - Defines no border, hidden - Defines a hidden border
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```

# CSS height and width

```html
auto - This is default. The browser calculates the height and width
length - Defines the height/width in px, cm, etc.
% - Defines the height/width in percent of the containing block
initial - Sets the height/width to its default value
inherit - The height/width will be inherited from its parent value
div {
  height: 200px;
  width: 50%;
  background-color: powderblue;
}
This element has a height of 200 pixels and a width of 50%
div {
  max-width: 500px;
  height: 100px;
  background-color: powderblue;
}
The max-width property is used to set the maximum width of an element.
```

# CSS box model

The CSS box model is essentially a box that wraps around every HTML element. It consists of: content, padding, borders and margins.

```html
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```

# CSS fonts

how to adjust fonts in CSS.

```html
.p1 {  font-family: "Times New Roman", Times, serif;}
.p2 {  font-family: Arial, Helvetica, sans-serif;}
.p3 {  font-family: "Lucida Console", "Courier New", monospace;}
```

# CSS links

ways of styling links in CSS.

```html
/* unvisited link */
a:link {
  color: red;
}

/* visited link */
a:visited {
  color: green;
}

/* mouse over link */
a:hover {
  color: hotpink;
}

/* selected link */
a:active {
  color: blue;
}

```