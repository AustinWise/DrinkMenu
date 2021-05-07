# Austin' Drink Menu

Some of my favorite cocktail recipes. Some of them are based on drinks
I've encountered in San Francisco and San Jose. This drink menu was often
used on sky tricks, so there are variety of winter drinks.

See the [releases](https://github.com/AustinWise/DrinkMenu/releases) for PDF
downloads of the menu.

## How to turn TeX into PDF

There are two versions of the menu: one with instruction for the bar tender and
one without. The instructions can be hidden by commenting out the contents of
the `HowTo` macro command.

1. Install [MiKTeX](https://miktex.org/)
1. Run `xelatex menu.tex`
1. Run `xelatex menu.tex`

For some reason the border does not show up the first time you run `pdflatex`.

I tried to run this on Ubuntu 18.04 with the `texlive-full` package installed,
but the font for the corner decorations was missing.
