# st - simple terminal

st is a simple terminal emulator for X.

This is my own custom build of [st](https://st.suckless.org/).
Below are patches added.

## Patches

* [boxdraw](https://st.suckless.org/patches/boxdraw/): Better rendering for lines / blocks / braille characters; (Latest ver: [0.8.5](https://st.suckless.org/patches/boxdraw/st-boxdraw_v2-0.8.5.diff))
* [ligatures](https://st.suckless.org/patches/ligatures/): Enable ligatures; (Latest ver: [0.8.4](https://st.suckless.org/patches/ligatures/0.8.4/st-ligatures-boxdraw-20210824-0.8.4.diff))
* [alpha](https://st.suckless.org/patches/alpha/): Allow transparency; (Latest ver: [20240814](https://st.suckless.org/patches/alpha/st-alpha-20240814-a0274bc.diff))
* [scrollback](https://st.suckless.org/patches/scrollback/): Scroll back through previous terminal output; (Latest ver: [0.9.2](https://st.suckless.org/patches/scrollback/st-scrollback-0.9.2.diff))
* [glyph wide support](https://st.suckless.org/patches/glyph_wide_support/): Fix unicode being chopped, mostly for nerd font symbols; (Latest ver: [20220411](https://st.suckless.org/patches/glyph_wide_support/st-glyph-wide-support-boxdraw-20220411-ef05519.diff))
* [anysize](https://st.suckless.org/patches/anysize/): Balance borders and centered terminal content correctly; (Lastest ver: [0.8.4](https://st.suckless.org/patches/anysize/st-anysize-0.8.4.diff))
* [bold is not bright](https://st.suckless.org/patches/bold-is-not-bright/): Display bold fonts as bold rather than making it brighter color; (Latest ver: [20190127](https://st.suckless.org/patches/bold-is-not-bright/st-bold-is-not-bright-20190127-3be4cf1.diff))
* [font2](https://st.suckless.org/patches/font2/): For adding fallback fonts; (Latest ver: [0.8.5](https://st.suckless.org/patches/font2/st-font2-0.8.5.diff))
* [externalpipe](https://st.suckless.org/patches/externalpipe/): Read and write st output through pipe; (Latest ver: [0.8.5](https://st.suckless.org/patches/externalpipe/st-externalpipe-0.8.5.diff))

## Installation

```
$ git clone https://github.com/wongweilok/st.git
$ cd st
$ sudo make clean install
```
