# computer-systems

## About

These are my revision notes for the Computer Systems module of the MSc Computer Science postgraduate course at the University of Birmingham during the 2020&ndash;2021 session.

## Getting Started

### Prerequisites

It is recommended to use [pdfTeX](http://tug.org/applications/pdftex/) to generate a PDF file directly from the source.
The pdfTeX extension is included in most [free TeX distributions](http://www.tug.org/interest.html#free).

### Installation

Simply clone the source from this repository.

```shell
git clone https://github.com/martindes01/computer-systems.git
cd computer-systems
```
### Files

- Main LaTeX file: [computer-systems.tex](computer-systems.tex)
- Compiled PDF: [computer-systems.pdf](computer-systems.pdf)

## Usage

To generate the PDF, run pdfTeX with the command `pdflatex` to use the standard LaTeX macros.
Two passes are needed to generate all features of the document.

```shell
pdflatex computer-systems.tex
pdflatex computer-systems.tex
```

## License

This project is distributed under the terms of version 3 of the GNU General Public License as published by the Free Software Foundation.
See [COPYING](COPYING) for more information.
