# minimal-blog-css

A *really* minimal CSS theme for blogs or other text-heavy websites.

Inspired by http://bettermotherfuckingwebsite.com/

You can view a demo at https://minimal-blog-css.netlify.app/

# Goals

 - Be readable; the CSS should make for a comfortable reading experience
 - Be portable; the reading experience should well to different devices and
   browsers
 - Be accessible; text should be clear and styles should not interfere with
   accessibility tools
 - Be minimal; better to include too little than too much

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

# Help wanted

I don't know much about typography and I'm not a designer. Suggestions and pull
requests are highly welcome!
