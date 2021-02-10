# Mita—a hugo theme that feels like a milligram.

You can check the demo [here.](https://mita-demo.netlify.app)

![mita first image](https://raw.githubusercontent.com/vinliao/mita/master/images/mita-1.png)
![mita second image](https://raw.githubusercontent.com/vinliao/mita/master/images/mita-2.png)

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
