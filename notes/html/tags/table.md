# `<table>`

Represents tabular data - presented in 2D table comprised of rows and columns of cells.

```html
<table>
  <thead>
    <tr>
      <th colspan="2">The table header</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>The table body</td>
      <td>with two columns</td>
    </tr>
  </tbody>
</table>
```

Permitted content:

1. Optional `<caption>` element.
2. 0 or more `<colgroup>` elements.
3. Optional `<thead>` element.
4. either one of:
    * 0 or more `<tbody>` elements.
    * 1 or more `<tr>` elements.
5. Optional `<tfoot>` element.
