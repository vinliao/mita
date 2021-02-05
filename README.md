# Mita—a hugo theme that feels like a milligram.

You can check the demo [here.](https://google.com)

![mita first image](https://raw.githubusercontent.com/vinliao/mita/master/images/mita-1.png)

## How to install
1. On your website's root directory, run `git submodule add https://github.com/vinliao/mita themes/mita`
2. In your `config.toml`, change the theme property to `theme = "mita"`

## How to add items in nav
Paste this to your `config.toml` and adjust accordingly.

```
[Menus]
  main = [
      {Name = "about", URL = "/about"},
      {Name = "other", URL = "/other"},
  ]
```

## Warning!
This theme is still at its infancy; it has lots of inconvenient bugs like spacing and layout issues.

But it's fairly okay for text-only blog, though.

Some known bugs/ugliness:
1. Long website title doesn't play well with the `max-width` css property.
2. The colors, even when there's not much of it, sucks.
3. All code-related texts are broken.
4. Some elements feel cramped: ul, ol, blockquote, and the bottom of website.
