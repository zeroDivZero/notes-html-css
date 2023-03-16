# `<img>`

Specifies an image. Type of void element: No content, no end tag.

## Source

Can be local file or URL:

```html
<img src="logo.png" />
```

## Dimensions

```html
<img src="photo.jpg" width="1024" height="768" />
```

Only specify one dimension for browser to maintain aspect ratio.

Use percentage to specify dimension relative to element containing image:

```html
<img src="photo.jpg" width="50%" />
```

Can use CSS. Following means 50% of container width:

```css
img {
  width: 50%;
}
```

## A11y

Alternative text if image fails to load, for a11y, and for SEO. Important.

```html
<img src="http://some.image.location" alt="this is an image of a cat" />
```
