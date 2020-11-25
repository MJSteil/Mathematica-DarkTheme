# Mathematica-DarkTheme

This repository includes a *Mathematica* stylesheet `DarkTheme.nb` including a dark themed *style/screen environment* named *WorkingDark*
which can be switched on and off using either the menu `Format->Screen Environment->...` or the command `SetOptions[EvaluationNotebook[],ScreenStyleEnvironment->"..."]`.
The same stylesheet is embedded as private style definitions in the notebook `Nootebook_DarkTheme_embedded.nb` which can be used without installing the stylesheet.

## Installation
Clone the repository `git clone https://github.com/MJSteil/Mathematica-DarkTheme.git`
and/or add `DarkTheme.nb` to the folder `$UserBaseDirectory\SystemFiles\FrontEnd\StyleSheets` or use/modify `Nootebook_DarkTheme_embedded.nb` to use the embedded version of the stylesheet, which does not require installation.

## Source structure
* **DarkTheme.nb:** Stylesheet

* **Nootebook_DarkTheme_embedded.nb:** Example notebook including an embedded version of the stylesheet using private style definitions.

## Example: `Nootebook_DarkTheme_embedded.nb`

<img src="doc/notebook.png" alt="Nootebook_DarkTheme_embedded.nb screenshot" width="800"/>

## Example: `DarkTheme.nb`

<img src="doc/stylesheet.png" alt="DarkTheme.nb screenshot" width="400"/>

## License
MIT License

Copyright 2020 Martin J. Steil

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
