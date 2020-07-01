# Kenney Icon Font for Hugo

**This is not a standalone theme.** This is a [Hugo](https://gohugo.io/) theme component that allows the use of the [Kenney Icon Font](https://github.com/nicodinh/kenney-icon-font). It includes the font, stylesheet and a shortcode.

![Shortcode sample screenshot.](https://gitlab.com/rmaguiar/hugo-kenney-icon-font/-/raw/master/demo/screenshot.png)

There's also a [PDF file](https://gitlab.com/rmaguiar/hugo-kenney-icon-font/-/raw/master/demo/cheatsheet.pdf) available for reference.

## Installation

1. Add the `hugo-kenney-icon-font` as a submodule:

```
git submodule add https://gitlab.com/rmaguiar/hugo-kenney-icon-font.git themes/kenney-icon-font
```

2. Add the `kenney-icon-font` in your config file. Example (as config.toml):

```toml
theme = [ "kenney-icon-font", "my-theme" ]
```

3. Make sure to load the `css/kenney-icons.css` somewhere. Example: 

```html
<link rel="stylesheet" href="{{ "css/kenney-icons.css" | absURL }}">
```

4. You should now be able to use the `ki` shortcode. Example:

```
{{< ki dpad-top dpad-top dpad-bottom dpad-bottom dpad-left dpad-right dpad-left dpad-right button-b button-a >}}
```

## Thanks to

* [Kenney.nl](http://kenney.nl/) & [@SamBrishes](https://github.com/SamBrishes) for the assets;
* [@nicodinh](https://github.com/nicodinh) for the icon font.