# osx-theme(1)

A script to change a Base16-based theme across all applications on OS X.

## How to install

osx-theme(1) is a [shell script][bin], so installation is simple.  [Download][download], extract and copy the script in the `bin` directory over to the `/usr/local/bin` directory and make sure it's in your `$PATH`.

## One-line installation

```bash
$ bash -c "$(curl -#fL raw.github.com/iamnewton/osx-theme/go/install)"
```

N.B. - using the one-line installation will download and install all of the dependencies.

## Usage

```bash
$ osx-theme [theme] [dark|light]
```

If no theme is specified, it will use the default located at the top of the file. Same is true for the style, if neither 'dark' nor 'light' are specified, 'light' is chosen by default.

## Applications Included

* ~~atom~~
* ~~bbedit~~
* ~~chrome-devtools~~
* ~~codemirror~~
* ~~console2~~
* ~~drracket~~
* ~~emacs~~
* ~~geany~~
* ~~gedit~~
* ~~gimp-palette~~
* ~~gnome-terminal~~
* ~~guake~~
* ~~highlight.js~~
* ~~idea~~
* ~~ipython-notebook~~
* iterm2
* ~~konsole~~
* marked2
* ~~mate-terminal~~
* ~~mintty~~
* ~~mmdc2~~
* ~~mou~~
* ~~notepad-plus-plus~~
* OS X color palette
* ~~prettify.js~~
* ~~preview~~
* ~~prism~~
* ~~putty~~
* ~~pygments~~
* ~~qtcreator~~
* ~~rainbow~~
* ~~rouge~~
* ~~secure-shell~~
* ~~shell~~
* terminal-app
* ~~terminator~~
* ~~termite~~
* ~~textadept~~
* ~~textmate~~
* ~~vconsole~~
* vim
* ~~visual-studio~~
* ~~windows-command-prompt~~
* xcode4
* ~~xfce4-terminal~~
* ~~xresources~~
* ~~zathura~~

## Acknowledgements

Inspiration and code was taken from many sources, including:

* [@chriskempson](https://github.com/chriskempson) (Chris Kempson) https://github.com/chriskempson/base16

[bin]: https://github.com/chrisopedia/osx-theme/blob/master/osx-theme
[download]: https://github.com/chrisopedia/osx-theme/archive/master.zip
