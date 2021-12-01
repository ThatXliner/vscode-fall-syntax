# Fall Syntax for VSCode

This is an almost-perfect port of [Fall Syntax][fs] v2.7.0. The reason why it may not match the original theme is because some decisions make a bit more sense (e.g. CoffeeScript methods not being highlighted purple).

I still have some decisions about the original theme to make so for now, this theme will only try to match as close to version 2.7 of Fall Syntax, deviating due to better decisions as described above.

*But not even a syntax theme can hide the ugliness of VSCode*

[fs]: https://github.com/ThatXliner/fall-syntax

## Installation

Until I upload this to the [marketplace](https://marketplace.visualstudio.com/vscode), here is a `git clone`-based solution/hack:

```bash
$ git clone https://github.com/ThatXliner/fall-syntax-vscode.git $HOME/.vscode/extensions/thatxliner.fall-syntax-vscode
```

To update, just run

```bash
$ git -C $HOME/.vscode/extensions/thatxliner.fall-syntax-vscode pull
```
