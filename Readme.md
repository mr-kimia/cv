# About #

This is ongoing version of my CV. I try to keep it up-to-date, but can not
promise that it always represents the current state of my professional life.
The template is created by [Adrien Friggeri][afriggeri] and it is available on
[GitHub][afriggerighcv].

You can find the [compiled pdf version][cvpdf] from my web site [kimia.fi][kimia.fi].

## Building on OS X ##

It seems that by default xelatex on os x can't find fonts. Open Font Book
application, create new library and add fonts from directory
`/usr/local/texlive/2015/texmf-dist/fonts/`. After that everything should work
by running `latexmk -xelatex -f cv`

# About original template #

Latest version of my CV, typesetted in Helvetica and using colors inspired by
Monokai (there is an `print` option which renders in black and white, and
reverts the header to dark on light, if printing on paper is needed).

Uses TikZ for the header, XeTeX and fontspec to use Helvetica Neue, biblatex to
print my publications and textpos for the aside.

# License #

Copyright (C) 2012, Adrien Friggeri

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[afriggeri]: http://www.friggeri.net/ "Adrien Friggeri"
[afriggerighcv]: https://github.com/afriggeri/CV "afriggeri/cv"
[kimia.fi]: http://kimia.fi "Personal home of Kimmo Ahokas"
[cvpdf]: http://kimia.fi/papers/cv.pdf "CV of Kimmo Ahokas"
