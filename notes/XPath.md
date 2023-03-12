# XPath

**XML Path Language**. Query language for selecting nodes in XML document. Works on HTML doc as well.Uses non-XML syntax. Can also be used to test if nodes match pattern.

## Example

```html
<html>
  <head>
    <title>Some webpage</title>
  </head>
  <body>
    <p class="normal">This is the first paragraph</p>
    <p class="special">This is the second paragraph. <b>This is in bold.</b></p>
  </body>
</html>
```

![XPath Example](/assets/xpath.png)

`/html/head/title`: Yields node with one child - text "Some webpage."

`/html/body/p[@class='special']`: Returns second paragraph. If multiple `<p>` tags have same class, returns array of nodes.
