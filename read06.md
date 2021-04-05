![img1](https://miro.medium.com/max/2625/1*cY0_-WhPUzPDGrczxV7fzA.png)

# **HTML CSS Color**

The color property defines the text color (foreground color in general) of an element.

For instance, the color property specified in the body selector defines the default text color for the whole page

# **Defining Color Values**

Colors in CSS most often specified in the following formats:

* a color keyword - like "red", "green", "blue", "transparent", etc.
* a HEX value - like "#ff0000", "#00ff00", etc.
* an RGB value - like "rgb(255, 0, 0)"

CSS3 has introduced several other color formats such as HSL, HSLA and RGBA that also support alpha transparency. We'll learn about them in greater detail in CSS3 color chapter.

For now, let's stick to the basic methods of defining the color values

# **Color Keywords**

CSS defines the few color keywords which lets you specify color values in an easy way.

These basic color keywords are: aqua, black, blue, fuchsia, gray, green, lime, maroon, navy, olive, purple, red, silver, teal, white, and yellow. The color names are case-insensitive.

**Example**

h1 {
    color: red;
}
p {
    color: purple;
}

Modern web browsers however practically support many more color names than what are defined in the CSS standard, but to be on the safer side you should use hex color values instead.

See the reference on CSS color names, for a complete list of possible color names.

# **HEX Color Values**

Hex (short for Hexadecimal) is by far the most commonly used method of defining color on the web.

Hex represent colors using a six-digit code, preceded by a hash character, like #rrggbb, in which rr, gg, and bb represents the red, green and blue component of the color respectively.

The value of each component can vary from 00 (no color) and FF (full color) in hexadecimal notation, or 0 and 255 in decimal equivalent notation. Thus #ffffff represents white color and #000000 represents black color.

**Example**

h1 {
    color: #ffa500;
}
p {
    color: #00ff00;
}

# **RGB Color Values**

Colors can be defined in the RGB model (Red, Green, and Blue) using the rgb() functional notation.

The rgb() function accepts three comma-separated values, which specify the amount of red, green, and blue component of the color. These values are commonly specified as integers between 0 to 255, where 0 represent no color and 255 represent full or maximum color.

**Example**

h1 {
    color: rgb(255, 165, 0);
}
p {
    color: rgb(0, 255, 0);
}

# **Affect of Color Property on Borders and Outlines**

The color property is not just for text content, but for anything in the foreground that takes a color value. For instance, if border-color or outline-color value hasn't been defined explicitly for the element, the color value will be used instead.

**Example**

p.one {
    color: #0000ff;
    border: 2px solid;
}
p.two {
    color: #00ff00;
    outline: 2px solid;
}

