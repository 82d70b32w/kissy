![Kissy terminal](https://i.postimg.cc/1RNFRP5F/kissy.jpg "kissy terminal")

## About

Kissy was created primarily because of the problem of finding an terminal emulator for X with _quality font rendering_ and the ability to display images like Kitty. So, here it is. Based on st 0.8.4. I don't use Xorg anymomore, so there won't be any changes. If you value hardware acceleration, lowest possible resource consumption, integrated tabs, then you'd better look at Wezterm, or other emulators like foot.

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

## Usage

```
git clone https://github.com/w23b07d28/kissy && cd kissy && sudo make clean install
```

## Disclaimer

One clipboard for terminal and browser breaks [freedesktop standard](http://standards.freedesktop.org/clipboards-spec/clipboards-latest.txt). And it was a bad decision. This means that you can copy things between the browser and the terminal, but if you decide to close the application, the clipboard also disappears. This is why it's useful to have a clipboard manager, and most likely why it was created. Don't make my mistake.

Please note that Kissy is not and will not ever more in development and may not be suitable for use in production environments. The author takes no responsibility for any damages that may occur as a result of using this script. Use at your own risk.
