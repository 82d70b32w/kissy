# Kissy Terminal

![Kissy terminal](https://i.postimg.cc/1RNFRP5F/kissy.jpg "kissy terminal")

## About

Kissy is the [suckless terminal (st)](https://st.suckless.org/) fork with some features and love.

I haven't finished it yet, but I don't have time at the moment. Download at your own risk.

## Motivation

I wanted to make something that doesn't turn computers into ovens, so I found a "literally the best terminal emulator ever" made a better one. Not really, because I'm not fluent in C and the project has been kind of abandoned. I switched to Wayland, so if you decide to install what you find here, be aware of the lack of updates and spaghetti inside.

## Features

- **Different name**, so you don't have to overwrite st;
- **Font matches your system font**;
- **Emoji support**, requires harfbuzz;
- **Scrolling just with mouse wheel**. Done without an external program like [scroll](https://tools.suckless.org/scroll/), which I've seen in other builds, but is currently more of a compromise than a seamless solution IMO;
- **Background transparency**, but requires a compositor;
- **Better vertical alignment**, means centered;
- **Option to open at specific directory** with `kissy -d`;
- **Desktop icon**;
- **Clipboard integration** with web browser;
- **W3M images hack**;
- **Clears the window before the redraw** of the terminal ofc;
- **Bold is not bright**;
- **Copy URL with a shortcut**;
- **More visually appealing text selection** while using mouse/touchpad;
- **Xresources support**.

## Facts

- The word `kissy` is a combination of the acronym "**K**eep **I**t **S**imply, **S**tupid", which refers to the philosophy of suckless tools and my second :-) favorite terminal emulator, [kitty](https://sw.kovidgoyal.net/kitty/);
- It was supposed to be part of a larger project;
- It's based on version 0.8.4 of st, but I've messed it up a bit and it's better to do the patches manually.;
- One clipboard for terminal and browser breaks the [freedesktop standard](http://standards.freedesktop.org/clipboards-spec/clipboards-latest.txt). All in the name of convenience and laziness which turned out to be a bad idea in the long run;
- By not reporting issues you make my life more comfortable in general;
- Bloat meter: less than _OMG LOC_;

## Installation

```
$ git clone https://github.com/phloox/kissy && cd kissy && make clean install
```

## To do (It will never happen)

- VI / IJKL bindings ...
- ... Generally arranging shortcuts. Yup, messed a bit;
- Functions useful for bash scripts;
- Hardcoded desktop icon;
- Corrections to default color palette;
- Window behavior while using TWM;
- Tabs.
