#  Doxygen Awesome for Doxygen 1.8.17

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/jothepro/doxygen-awesome-css)](https://github.com/jothepro/doxygen-awesome-css/releases/latest)
[![GitHub](https://img.shields.io/github/license/jothepro/doxygen-awesome-css)](https://github.com/jothepro/doxygen-awesome-css/blob/main/LICENSE)
![GitHub Repo stars](https://img.shields.io/github/stars/jothepro/doxygen-awesome-css)

<div style="filter: drop-shadow(0px 3px 10px rgba(0,0,0,0.22)); max-width: 500px">

![Screenshot of Doxygen Awesome CSS](img/screenshot.png)

</div>

**Doxygen Awesome** is a custom **CSS theme for Doxygen HTML-documentation** with lots of customization parameters.

## Motivation

I really like how the Doxygen HTML-documentation is structured! But IMHO it looks a bit outdated.

This theme is an attemt to update the visuals of Doxygen without changing it's overall layout too much.

**Fixed for Doxygen 1.8.17**

## Features

- 🌈 Clean, modern design
- 🚀 Heavily customizable by adjusting CSS-variables
- 🧩 No changes to the HTML structure of Doxygen required
- 📱 Improved mobile usability
- 🌘 Dark mode!
- 🥇 **Works with Doxygen 1.8.17, have not tested with other versions.**

## Installation

Copy the file `doxygen-awesome.css` from this repository into your project or add this repository as submodule and check out the latest release:

```bash
git submodule add https://github.com/jowharshamshiri/doxygen-awesome-css.git
cd doxygen-awesome-css
git checkout v2.0.3
```

```
# Doxyfile
GENERATE_TREEVIEW      = YES # optional. Also works without treeview
HTML_EXTRA_STYLESHEET  = doxygen-awesome-css/doxygen-awesome.css
```

Further installation instructions:

- [How to install extensions](docs/extensions.md)
- [How to customize the theme (colors, spacing, border-radius, ...)](docs/customization.md)
- [Tips and Tricks for further configuration](docs/tricks.md)

## Browser support

Tested with

- Chrome 98, Chrome 98 for Android, Chrome 87 for iOS
- Safari 15, Safari for iOS 15
- Firefox 97, Firefox Daylight 97 for Android, Firefox Daylight 96 for iOS

## Credits

- This theme is inspired by the [vuepress](https://vuepress.vuejs.org/) static site generator default theme.
- Thank you for all the feedback on github!

<span class="next_section_button">

Read Next: [Extensions](docs/extensions.md)
</span>
