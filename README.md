# minimal-blog-css

A *really* minimal CSS theme for blogs or other text-heavy websites.

Inspired by http://bettermotherfuckingwebsite.com/

# How to use

Just include the `minimal-blog.css` file on your website and enjoy a minimal
but readable layout.

You'll probably also want to use the ["viewport
meta"](https://developer.mozilla.org/en-US/docs/Web/HTML/Viewport_meta_tag) tag
to make it display properly on mobile.

```html
<head>
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" href="minimal-blog.css" />
</head>
```

To make hyphenations work, make sure to set the [lang
attribute](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang)
to whatever language your content is written in, e.g.

```html
<html lang="en">
```
