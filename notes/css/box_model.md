# BOX MODEL

![Box Model](/assets/box-model.png)

Every element is rectangular box.

## [Size](./properties/width_and_height.md)

Innermost content size.

```css
height: 200px;
width: 30em;
```

## [Padding](./properties/padding.md)

Pads content with space additional to content size but not background.

```css
padding: 5px 1em 0 2em;
```

## [Border](./properties/border/border.md)

Needs at least style to appear.

```css
border-style: solid;
border-width: 5px;
border-color: red;
```

Or use shorthand (cannot specify side):

```css
border: 5px solid red;
```

## [Margin](./properties/margin.md)

Extra space outside border to separate from adjacent elements.

```css
margin: 5% auto;
```

## Values

### Unit

Pixels (px), percentage of parent (%), ephemeral unit (em) (font size), etc.

### Side

For padding, border, and margin, can specify 1-4 values.
1 value: applies to all 4 sides
2 values: first applied to top bottom, second to left right
3 values: first applied to top, second to left right, third to bottom
4 values: applied to top, right, bottom, left (clockwise)

Or, add suffix (or in case of border, in middle) `-top`, `-right`, `-bottom`, `-left` to specify single side.
