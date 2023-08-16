# SELECTOR

## Element Selector

Selects particular HTML tag. Applies to all elements of that tag:

```css
p {
  color: blue
}
```

## Class Selector

Selects elements of that class (grouping specified with attribute `class`):

```css
.red-text {
  color: red
}
```

```html
<h2 class="red-text">Red</h2>
```

## Id Selector

Selects element(s) with `id` attribute:

```css
#main {
  color: red
}
```

```html
<h1 id="main">Header</h1>
```

`id` should be unique per HTML file.

## Attribute Selector

Selects all elements of that tag with specified attribute:

```css
p[draggable] {
  color: red
}
```

```html
<p draggable="true">Drag Me</p>
```

Can select with particular attribute value:

```css
p[draggable="false"] {
  color: blue
}
```

## Universal Selector

Selects all:

```css
* {
  color: red
}
```
