# `font-size`

<https://developer.mozilla.org/en-US/docs/Web/CSS/font-size>

## Absolute Size

```css
h1 {
  font-size: large
}
```

Use absolute-size keyword, from `xx-small` to `xxx-large` (default `medium`).

## Relative Size

```css
h1 {
  font-size: smaller
}
```

Use relative-size keyword, `smaller` or `larger`, relative to parent size.

## Length

```css
h1 {
  font-size: 16px
}
```

| Unit | Length         |
| ---- | -------------- |
| 1px  | 1/96 inch      |
| 1pt  | 1/72 inch      |
| 1em  | 100% of parent |
| 1rem | 100% of root   |

## Percentage

```css
h1 {
  font-size: 90%
}
```

Positive percentage value relative to parent size.
