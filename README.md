# Awesome Python Terminal [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A list of awesome Python frameworks and libraries for interacting with the console. A lot of these libraries have functionality in common which makes it hard to put them into sections... but I tried.


## Argument Parsing
*Go beyond argparse with these incredible libraries*

* [argparse](https://docs.python.org/3/library/argparse.html) - Built in
* [click](https://github.com/pallets/click) - (11k)
* [docopt](https://github.com/docopt/docopt) - (7k) Declarative approach
* [fire](https://github.com/google/python-fire) - (20k) Add a CLI to any object
* [typer](https://github.com/tiangolo/typer) - (6k) Add functions to CLI by decorating them

## Terminal Rendering
*Who'd have thought that the terminal is copable of rendering all these?*

* [huepy](https://github.com/s0md3v/huepy) - (0.4k) Colored text (There are many more like this)
* [colr](https://github.com/welbornprod/colr) - Colored text in RGB
* [colorama](https://github.com/tartley/colorama) - (3k) Makes ANSI colors work on windows
* [rich](https://github.com/willmcgugan/rich) - (28k) Has got a bit of everything
* [bashplotlib](https://github.com/glamp/bashplotlib) - (2k) Plots in the terminal
* [emoji](https://github.com/carpedm20/emoji) - (1k) Emojis in terminal
* [mdv](https://github.com/axiros/terminal_markdown_viewer) - (2k) Markdown in terminal

## Progress Bars
*Add progress to loops. Don't ask me why we got so many libraries for this*

* [progress](https://github.com/verigak/progress/) - (1k) Fancy
* [progressbar](https://github.com/WoLpH/python-progressbar) - (0.7k) Extra Fancy
* [tdqm](https://github.com/tqdm/tqdm) - (19k) Extremely Fancy
* [alive-progress](https://github.com/rsalmei/alive-progress) - (3k) Ridiculously Fancy
* [halo](https://github.com/manrajgrover/halo) - (3k) Without the bar, just spinners
* [fastprogress](https://github.com/fastai/fastprogress) - (1k) Also being targeted Jupyter Notebook
* \+ rich + prompt_toolkit

## CLI
*These combine a bit of everything*

* [cmd](https://docs.python.org/dev/library/cmd.html) - Built in
* [prompt_toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) - (7k) Borderline TUI
* [questionary](https://github.com/tmbo/questionary) - (0.7k) Create pretty user prompts
* [pyinquirer](https://github.com/CITGuru/PyInquirer) - (1k) Cool
* [cement](https://github.com/datafolklabs/cement) - (1k) Well documented and extensive

## TUI
*Like GUI but in your console*

* [curses](https://docs.python.org/dev/library/curses.html) - Built in on linux
* [textual](https://github.com/willmcgugan/textual) - (4k) Based on rich
* [urwid](https://github.com/urwid/urwid) - (2k) Solid
* [asciimatics](https://github.com/peterbrittain/asciimatics) - (3k) Also has fancy ASCII animations
* [blessed](https://github.com/jquast/blessed) - (0.7k) Based on curses, but it's like blessed... get it?
* [npyscreen](https://github.com/npcole/npyscreen) - (0.4k) A classic but now unmaintained library

## Miscellaneous
*Cool libs that don't fit anywhere else*

* [pexpect](https://github.com/pexpect/pexpect) - (2k) Control other terminal programs
* [gooey](https://github.com/chriskiehl/Gooey) - (15k) Automagically give your command line program a GUI
* [clime](https://pypi.org/project/clime/) - Automagically give your module a command line interface
