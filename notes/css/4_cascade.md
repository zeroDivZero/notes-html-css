# CASCADE

When multiple CSS styles applied to same element, actual styles taking effects based on priority. 4 categories: **position** > **specificity** > **type** > **importance**.

## Position

If rule is at higher or lower position. Lower one (either in same `{}` or outside) wins.

## Specificity

How specific rule is. Id selector > attribute selector > class selector > element selector.

## Type

How style's added. Inline > internal > external.

## Importance

For style that trumps all others, specify keyword `!important`.

```css
color: red;
color: green !important;
```
