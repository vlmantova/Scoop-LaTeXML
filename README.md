# Scoop bucket for LaTeXML

[![Tests](https://github.com/vlmantova/Scoop-LaTeXML/actions/workflows/ci.yml/badge.svg)](https://github.com/vlmantova/Scoop-LaTeXML/actions/workflows/ci.yml) [![Excavator](https://github.com/vlmantova/Scoop-LaTeXML/actions/workflows/excavator.yml/badge.svg)](https://github.com/vlmantova/Scoop-LaTeXML/actions/workflows/excavator.yml)

A bucket for installing LaTeXML on Windows using the [Scoop](https://scoop.sh/). The following packages are included:
- `perl-Image-Magick`
- `perl-Image-Size`
- `perl-LaTeXML`
- `perl-c-bin`: empty package to add Perl's `c\bin` directory to the user PATH

## Usage
```pwsh
scoop bucket add LaTeXML https://github.com/vlmantova/Scoop-LaTeXML
scoop install perl-LaTeXML
scoop install perl-Image-Magick # optional
```
