## Ru


**IMPORTANT NOTICES FOR VERSION 1.0**

* The `title format` values have been restructured. Please refer to the
  [manual][].

---

Ru is a simple, modern Beamer theme suitable for anyone to use. It tries
to minimize noise and maximize space for content; the only visual flourish it
offers is an (optional) progress bar added to each slide. .

Not convinced? Have a look at the [demo slides][].

## Installation

<!-- To install a stable version of this theme, please refer to update instructions
of your TeX distribution. Ru is on [CTAN][] since December
2014 thus it is part of MikTeX and will be part of TeX Live 2016.
 -->
Installing Ru from source, like any Beamer theme, involves four easy
steps:

1. **Download the source** with a `git clone` of the [Ru repository](https://gitlab.science.ru.nl/benoit/rutheme) or as a [zip archive](https://gitlab.science.ru.nl/benoit/rutheme/repository/archive.zip?ref=master) of the latest development version.

2. **Compile the style files** by running `make sty` inside the downloaded
    directory. (Or run LaTeX directly on `source/rutheme.ins`.)

3. **Move the resulting `*.sty` files** to the folder containing your
   presentation. To use Ru with many presentations, run `make install`
   or move the `*.sty` files to a folder in your TeX path instead (might require
   `sudo` rights).

4. **Use the theme for your presentation** by declaring `\usetheme{ru}` in
    the preamble of your Beamer document.


## Usage

The following code shows a minimal example of a Beamer presentation using
Ru.

```latex
\documentclass{beamer}
\usetheme{ru}           % Use ru theme
\title{A minimal example}
\date{\today}
\author{Benoit Viguier}
\institute{Radboud University}
\begin{document}
  \maketitle
  \section{First Section}
  \begin{frame}{First Frame}
    Hello, world!
  \end{frame}
\end{document}
```

Detailed information on using Ru can be found in the [manual][].


## License

The theme itself is licensed under a [Creative Commons Attribution-ShareAlike
4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). This
means that if you change the theme and re-distribute it, you *must* retain the
copyright notice header and license it under the same CC-BY-SA license. This
does not affect the presentation that you create with the theme.


<!-- [demo slides]: http://mirrors.ctan.org/macros/latex/contrib/beamer-contrib/themes/metropolis/demo/demo.pdf
[manual]: http://mirrors.ctan.org/macros/latex/contrib/beamer-contrib/themes/metropolis/doc/metropolistheme.pdf
[CTAN]: http://ctan.org/pkg/beamertheme-metropolis -->
