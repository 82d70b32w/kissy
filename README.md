![Kissy terminal](https://i.postimg.cc/1RNFRP5F/kissy.jpg "kissy terminal")

## About
Kissy was created primarily because of the problem of finding an emulator for X with _quality font rendering_ and ability to display images like Kitty. So, there it is. Based on st 0.8.4.

I don't use Xorg anymore, so I don't think there will be any changes. If you value hardware acceleration, possibly lowest resource usage, integrated tabs, then you better take a look at Wezterm or other no non-sense emulators like foot.

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

## Important info
- One clipboard for terminal and browser breaks the [freedesktop standard](http://standards.freedesktop.org/clipboards-spec/clipboards-latest.txt).
