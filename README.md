# st - simple terminal

st is a simple terminal emulator for X which sucks less.

This is my own custom build of [st](https://st.suckless.org/).
Below are patches that I added into my st build.

## Patches

* [alpha](https://st.suckless.org/patches/alpha/): Allow transparency
* [anysize](https://st.suckless.org/patches/anysize/)
* [bold is not bright](https://st.suckless.org/patches/bold-is-not-bright/): Display bold fonts as bold rather than making it brighter color
* [boxdraw](https://st.suckless.org/patches/boxdraw/): Better rendering for lines / blocks / braille characters
* [font2](https://st.suckless.org/patches/font2/): For adding fallback fonts
* [scrollback](https://st.suckless.org/patches/scrollback/): Scroll back through previous terminal output
* [vertcenter](https://st.suckless.org/patches/vertcenter/): Vertically center lines

## Installation

```
$ git clone https://github.com/wongweilok/st.git
$ cd st
$ sudo make clean install
```
