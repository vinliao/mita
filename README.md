# Mita—the most boring (but gorgeous) hugo theme
There's one question that guided me in the process of making this theme. The question is this: "If I were to make a theme that can last decades, what would it look like?" The result is this hugo theme.

Boring on purpose:
- No fancy colors
- No categories
- No analytics
- No tracking
- No icons
- No tags
- No JS
- No BS

You can check the demo at [vinliao.com](https://vinliao.com).

![mita desktop](https://raw.githubusercontent.com/vinliao/mita/master/images/mita-desktop.png)

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

## On archive
This theme has an archive, but it’s not on `/posts` like where the usual hugo archive is located. The archive is a [shortcode](https://gohugo.io/content-management/shortcodes/). Here's how you can use it.

1. Run `hugo new archive.md`
2. On the `archive.md` file, delete `date` in the front matter, add `{{% archive %}}` in the body
3. You can access the archive at `yourwebsite.com/archive`

The end result of `archive.md` might look something like this:

```
---
title: "Archive"
draft: false
---
(Optional: you can put text here.)

{{% archive %}}
```

## Misc
- You can remove a page's date by deleting the `date` variable in the front matter. A post without date won't be listed on the front page, but still can be accessed - e.g., an about page.
- I built this theme from scratch. If you'd like to build your own hugo theme, I've written a tutorial [here](https://dev.to/vinliao/create-your-own-hugo-theme-from-scratch-5df9).
- If you find this project useful, consider buying me [coffee](https://buymeacoffee.com/vinliao).
