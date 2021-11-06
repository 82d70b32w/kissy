![Kissy terminal](https://i.postimg.cc/1RNFRP5F/kissy.jpg "kissy terminal")

## About
Kissy was created primarily because of the problem of finding for myself an emulator for X with _quality font rendering_ like Alacritty and ability to display images like Kitty.

Well, there it is. ¯\_(ツ)\_/¯

I don't use Xorg anymore, so I don't think there will be any changes. If you value hardware acceleration, possibly lowest resource usage, integrated tabs, then you better take a look at Wezterm.

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
- **Clears the window before the redraw** of the terminal
- **Bold is not bright**
- **Copy URL with a shortcut**
- **More visually appealing text selection** while using mouse/touchpad
- **Xresources support**

## Installation
```
git clone https://gitlab.com/jakubolszewski/kissy-terminal && cd kissy-terminal && sudo make clean install
```

## To do
- One clipboard for terminal and browser breaks the [freedesktop standard](http://standards.freedesktop.org/clipboards-spec/clipboards-latest.txt).
- Arranging shortcuts. Messed.
