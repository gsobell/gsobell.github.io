---
title: LaTeX
summary: My personal LaTeX templates
---
{{< katex >}}

[\\( \LaTeX \\)](https://en.wikipedia.org/wiki/LaTeX) is a document preparation system. It is particularly adept for typesetting math, and is both powerful and extensible.


I use `vim` + `zathura`, along with my GNU/Linux distribution 's [`texlive`](https://en.wikipedia.org/wiki/TeX_Live) package.

![sample](featured.png)

In order to save time, I wrote a [preamble.tex](https://github.com/gsobell/texplates/blob/home/preamble.tex) that I include in almost all my files. To access all its functionality is simple as adding `\input{./preamble}` to the top of the file.

Some of my templates:

### [Document Cover](https://github.com/gsobell/texplates/tree/home/cover-page)
Generate a cover for your document, inspired by the familiar standard GNU Documentation covers.

### [Bi-Directional](https://github.com/gsobell/texplates/tree/home/bidi-article)
For documents with bidirectional text. Example uses Hebrew, but good for any other RTL language. I prefer the explicitly delineated LTR and RTL blocks to the implicit ones found in most word processors, for ease of editing. Be sure to compile with [`XeLaTeX`](https://en.wikipedia.org/wiki/XeTeX) for unicode support.

### [fast-cv](https://github.com/gsobell/fast-cv)
_faster than making a cup of noodles_ :ramen:

A outline for a CV, without having to learn a new packages, new commands or mess around with installing `.sty` files.

Links:


{{< github repo="gsobell/texplates" >}}


{{< github repo="gsobell/fast-cv" >}}


