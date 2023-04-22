# `<nav>`

Section of navigation links. Common examples of navigation sections are menus, tables of contents, and indexes.

Not all links need to be in `<nav>`. Intended for major block of links. `<footer>` another example that often has links. Doc can have multiple nav sections.

Screen reader may use this to omit initial rendering of nav-only content.

## Example

Doesn't have to include only list, but common:

```html
<nav class="menu">
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

With right styling can be sidebar, navbar, dropdown, etc.
