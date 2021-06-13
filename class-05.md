# Images, Color, Text

# Images

To add an image into the page you need to use an < img > element. This is an empty element (which means there is no closing tag). It must carry the
following two attributes:

1. src

This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that
the images are in a child folder called images — relative URLs were covered on pages 83-84).

2. alt

This provides a text description of the image which describes the image if you cannot see it.

```
<img src="images/quokka.jpg" alt="A family of
quokka" title="The quokka is an Australian
marsupial that is similar in size to the
domestic cat." />
```

- Three Rules for Creating Images:

1. Save images in the right format
2. Save images at the right size
3. Use the correct resolution

- Note: Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

# color

How to specify colors?

Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.


Computer monitors are made up of thousands of tiny squares called pixels (if you look very closely at your monitor you should be able to see them).
When the screen is not turned on, it's black because it's not emitting any light. When it's
on, each pixel can be a different color, creating a picture. The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue —
just like on a television screen.

**CSS 3: HSL Colors

CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.

# Text

**Underst anding Font Formats

Different browsers support different formats for fonts (in the same way that they support different audio and video formats), so you will need
to supply the font in several variations to reach all browsers.

- Bold: font-weight

```
.credits {
font-weight: bold;}
```

- Italic: font-style

```
.credits {
font-style: italic;}
```

- UpperCase & LowerCase: text-transform

```
h1 {
text-transform: uppercase;}
h2 {
text-transform: lowercase;}
.credits {
text-transform: capitalize;}
```
- Underline & Strike: text-decoration

```
.credits {
text-decoration: underline;}
a {
text-decoration: none;}
```
- Leading: line-height

```
p {
line-height: 1.4em;}
```
- Lett er & Word Spacing: letter-spacing, word-spacing

```
h1, h2 {
text-transform: uppercase;
letter-spacing: 0.2em;}
.credits {
font-weight: bold;
word-spacing: 1em;}
```

- Alignment: text-align

```
h1 {
text-align: left;}
p {
text-align: justify;}
.credits {
text-align: right;}
```

- Indenting Text: text-indent

```
h1 {
background-image: url("images/logo.gif");
background-repeat: no-repeat;
text-indent: -9999px;}
.credits {
text-indent: 20px;}
```

