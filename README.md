# vight—a zero-nonsense hugo theme for writers

// todo: add screenshot

What this theme does not offer:
- categories and tags
- pagination
- icons and animations
- colorful things (there are colors, but not much)
- tracking with analytics
- dark mode
- javascript (for now... perhaps)

## How to install
1. On your website's root directory, run `git submodule add https://github.com/vinliao/vight themes/vight`
2. In your `config.toml`, change the theme property to `theme = "vight"`

## How to add items in nav
Paste this to your `config.toml` and adjust accordingly

```
[Menus]
  main = [
      {Name = "about", URL = "/about"},
      {Name = "other", URL = "/other"},
  ]
```
