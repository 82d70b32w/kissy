# Kissy Terminal

![Kissy terminal](https://i.postimg.cc/1RNFRP5F/kissy.jpg "kissy terminal")

## About

Kissy is the [suckless terminal](https://st.suckless.org/) fork. I found a "literally the best terminal emulator ever" and made a better one.

Not really, because I'm not fluent in C and switched to Wayland yet, so the project has been kind of abandoned. If you decide to install what you find here, be aware of the lack of updates and spaghetti™ inside. Also one clipboard for terminal and browser breaks the [freedesktop standard](http://standards.freedesktop.org/clipboards-spec/clipboards-latest.txt). Turned out to be a bad idea in the long run.

## Features

- **Different name**, don't have to overwrite st
- **Font matches your system font**
- **Emoji support**, requires harfbuzz
- **Scrolling just with mouse wheel**. Done without an external program like [scroll](https://tools.suckless.org/scroll/), which I've seen in other builds, but is currently more of a compromise than a seamless solution IMO
- **Background transparency**, but requires a compositor
- **Better vertical alignment**, means centered
- **Option to open at specific directory** with `kissy -d`
- **Desktop icon**
- **Clipboard integration** with web browser
- **W3M images hack**
- **Clears the window before the redraw** of the terminal ofc
- **Bold is not bright**
- **Copy URL with a shortcut**
- **More visually appealing text selection** while using mouse/touchpad
- **Xresources support**

## Installation

```
git clone https://gitlab.com/jakubolszewski/kissy-terminal && cd kissy-terminal && sudo make clean install
```

## To do

- Arranging shortcuts. Yup, messed.
- Hardcoded desktop icon
- Tabs
