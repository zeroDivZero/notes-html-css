# `<a>`

"Anchoring," defines hyperlink. Attribute `href` specifies linked location.

## Page (Internal or External)

```html
<a href="page2.html">Page 2</a>
<a href="https://www.google.com">Google</a>
```

Can wrap another element like image to make it linkable:

```html
<a href="http://link.to.somewhere">
  <img src="http://image.from.somewhere">
</a>
```

## Reload

Don't specify location to reload current page:

```html
<a href="">Reload</a>
```

## Dead Link

If link isn't known, as placeholder:

```html
<a href="#">Coming Soon</a>
```

## Location in Page

I. Add `id` to element. Or create anchor at desired location:

```html
<a name="chapter1"></a>
```

II. Link:

```html
<a href="index.html#chapter1">Chapter 1</a>
```

Can be `id` or anchor name. Specify webpage name if linking to another page. Ignore it (just use `#{anchor name}`) if linking to same page.

## Download

Add attribute `download` to make linked file downloadable. May not work if file not on same host.

```html
<a href="img-internal.jpg" download="img-external.jpg">Download Image</a>
```

If download name not specified, uses `href` name.

## Remove Text Underline

Style it:

```css
a {
  text-decoration: none;
}
```
