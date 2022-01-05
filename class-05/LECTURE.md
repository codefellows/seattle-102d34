# Class 05: CSS

## Review

- Lauren: You have to put a rule declaration inside a CSS curly brace.
- Jeffrey: The heading tag is not for making text bigger.
- Nicholas: Don't jump around, set it down consciously. 
- Alan: You can style your HTML without a style element or CSS file.
`<p style="background: pink;">Text</p>`
  - Is this CSS? Yes it, but it is missing some the expected CSS syntax things.
- Brady: It is important to place attributes in the correct place on the HTMl element.
- Liesl: HTML borders are very cool!
- Ella: Scheduled breaks are good, it's hard to take you mind of off some of these topics / problems.
- Robert: Is a styel attribute CSS?  How does sound work?
  - HTMl includes an `<audio src="/voices.mp3">`

## Cascading Style Sheets (CSS)

The langauge that describe how HTML elements look!

```html

<div id="intro">
  <p>color me blue!</p>
</div>

<p>I have no parent :(<p>

```

```css

#intro p, header {
  font-size: 10px;
  border: 2px dashed black;
  display: relative;
  color: blue;
}

li {
  font-size: 20px;
}

```

- `Rule`: All the CSS styling properties and values that tell an element of group of elements how to look.
- `Property`: something that an elements uses to describe how the element looks.
  - there is a (very big list).  We have to look these up to figure out how each property affects our elements. It goes in-between the curly brackets, makes up the rule.
- `Value`: what you assign to a property.  usually a single string or a pixel value. the other side of our colons. for string values we probably have to look these up. Sometimes there is more than value to a property.
- `Selector`: Precedes the rule in curly brackets, is used to select one or more elements in the HTML document.
- `Curly Brackets`, (compared to angle brackets): the rule for our selectors, is always withing a set of curly brackets.

## Color

- Using a color term that we know: red, blue, pink.. aqua, teal. interpreted by our browser and turned into (rgb) values.
- RGB: the additive values of red, green, blue.
`color: rgba(255, 255, 255, 1);`  - values in the rgb function are between 0 - 255.
- CYMK: the subtractive values of cyan, magenta, yellow, and black.
`color: cmyk(100%, 0%, 0%, 0%)` - uses percentages.
- Hex values: a six encoded string made up of characters (0 - f). Evert 2 character correspond to ( red/ green / blue ).
  - `#000000` - white
  - `#ffffff` - black
  - `color: #000000`;

[My Deployed Demo Code](https://github.com/JacobKnaack/102d34-class-04-deployment)
