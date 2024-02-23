# GrinHighlighter

This VSCode extension provides syntax highlighting support for GRIN, a programming language made as a project
for ICS 33 at UC Irvine.

***
***DISCLAIMER:* This repository does not contain ANY code from the actual project, nor does it guarantee that everything works in your program! Additionally, this repository contains no academically dishonest material and is simply syntactically derived from information directly available on the website linked below. This is also not submitted for credit in any way, and is the sole property of @abhi-arya1. Use this for *fun*!**
***

To install, first clone this repository with:
```bash
git clone https://github.com/abhi-arya1/GrinHighlighter.git
```
And then install by going to VSCode Extensions, clicking `Install from VSIX`, and use `grin-0.0.1.vsix` from this repo.
Then, any files you make ending in `.grin` will be highlighted accordingly!


Please note that any "chunk" statements in `GOTO` and `GOSUB` blocks (as seen on the website) must start with `f` such as 
```
fCHUNK: [operation]
```
for the highlighter to recognize them as a function!


Full GRIN Syntax can be found [here](https://ics.uci.edu/~thornton/ics33/ProjectGuide/Project3/)
