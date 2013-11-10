# Introduction

A Kate syntax highlighting file for FreeFem++.

This is mostly an update of this [edp.xml](http://www.cmap.polytechnique.fr/spip.php?article402)
file, using the vim syntax file found [here](https://github.com/holomorph/vim-freefem).
So thank you to those guys for the inspiration.

# Install

To install, just copy the file `edp.xml` to `~/.kde4/share/apps/katepart/syntax/`.
Create the folder if it does not exist.

There's also a mimetype file for edp files. Install with:
```bash
xdg-mime install freefem-edp.xml
```
and the run:
```bash
update-mime-database ~/.local/share/mime
```
Hopefully those are the correct locations on most systems. Adjust if necessary.
