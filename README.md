# Tinted Sketchbook

Inspired by [Play with your code](https://www.chael.codes/talks/2025/09/13/play-with-your-code.html) ([@ChaelCodes](https://github.com/ChaelCodes)), this is a lightweight tool for building your own editor themes!

The underlying tool is Base16, as currently maintained by the [Tinted project](https://github.com/tinted-theming).

## Terminology

_This took me forever to figure out, so I'm writing it down!_

* **Scheme**: The color palettes you're defining. [Learn more about Base16](https://github.com/tinted-theming/home/blob/main/styling.md)

* **Templates**: [Mustache](https://mustache.github.io) files used to render the files that you need for a particular app (such as Sublime Text, or iTerm2)

* **Builder**: A tool used to take **Schemes** and process them through **Templates**.

## Prerequisites

* An copy of the executable for `tinted-builder-rust` in this directory (you can install it from: https://github.com/tinted-theming/tinted-builder-rust)

## How to get started

Now that you have `tinted-builder-rust`, run:

```sh
./build
```

### Just see the swatch table:

Open one of the generated HTML files at: `templates/swatch/themes/`

### To see how it looks with code (Using Highlight.js)

Open one of the generated HTML files at: `templates/highlight-js/themes/`


_There is also a `./watch` script, that rebuilds every second._

Want a quick web server for the static files? Check out [WorldWideWeb](https://iconfactory.com/worldwideweb/) for macOS