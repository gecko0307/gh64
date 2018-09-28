# gh64
Minimized/stripped base64-encoded web font generator based on [glyphhanger](https://github.com/filamentgroup/glyphhanger). It was written to simplify CSS generation for embedding fonts into web pages.

Installation:
```
npm install -g glyphhanger
npm link
```

Usage:
* Copy `config` folder to working directory with your font(s) and edit `config/default.json`. It may look like this:
```
{
    "font1": {
        "fontFamily": "Your_font_name",
        "fontFile": "Your_font_name.ttf",
        "whitelist": "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    },
}
```
* Run `gh64` inside working directory. You'll get `fonts.css` file that you can use on your page.
