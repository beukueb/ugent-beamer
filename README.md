This is a fork of the LaTeX beamer theme for the [University of Ghent](http://ugent.be), based on [nschloe/ua-beamer](https://github.com/nschloe/ua-beamer).

The aim of the fork is slightly different: to provide a full, but minimal beamer theme
for the Ghent University. The minimal theme only provides the correct color setup per
faculty, and a custom title page with the faculty banner.
Another general purpose beamer theme can be used as template for the other frames.
This theme should be loaded before the UGent theme.

For example:

    \usetheme{AnnArbor}
    \usetheme[faculty=fw]{MinUGent}

To use the theme, either copy the necessary *.sty/images from the theme folder to
your presentation folder, or copy them to your tex theme folder.
On a linuxbox the following lines would accomplish the latter.

    git clone https://github.com/beukueb/ugent-beamer.git
    mkdir -p ~/texmf/tex/latex/beamer/themes/UGent/
    cp -r ugent-beamer/* ~/texmf/tex/latex/beamer/themes/UGent/
    texhash ~/texmf


