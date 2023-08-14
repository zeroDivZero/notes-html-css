# ADD

3 ways to add CSS to website.

## Inline

Directly add style in element. Not recommended because it mixes content with presentation.

```html
<p style="color: sienna; margin-left: 20px">This is a paragraph.</p>
```

## Internal

Single document has own unique style. In head section (by convention), define internal styles with `<style>`:

```html
<head>
     <style type="text/css">
          hr {color: sienna;}
          p {margin-left: 20px;}
          body {background-image: url("images/back40.gif");}
     </style>
</head>
```

## External

Rules saved in external `.css` file. Ideal when style applied to multiple pages. Can change look of entire site by changing one file. Each page must link to style sheet using `<link>` that goes inside head section:

```html
<head>
     <link href="mystyle.css" rel="stylesheet" type="text/css" />
</head>
```
