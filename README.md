# Python DocBlock Package
[![Build Status](https://travis-ci.org/spadarian/docblock-python.svg?branch=master)](https://travis-ci.org/spadarian/docblock-python)

DocBlock is a package for [Atom](https://atom.io) which helps you to document your python code.

![Demo](https://raw.githubusercontent.com/spadarian/docblock-python/master/img/demo.gif)

### Lint support

![Lint](https://raw.githubusercontent.com/spadarian/docblock-python/master/img/lint.png)

## Instalation

From the command line run `apm install docblock-python`. You can also install it from the [Atom Package manager](https://flight-manual.atom.io/using-atom/sections/atom-packages/#atom-packages).

## Available styles

* Numpy style: [A Guide to NumPy/SciPy Documentation](https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt).
* Google style: [Google Python Style Guide](http://google.github.io/styleguide/pyguide.html).
* Sphinx style: [Sphinx documentation](http://www.sphinx-doc.org/en/master/usage/restructuredtext/domains.html#info-field-lists).

## TODO

This is a non-exhaustive list of future additions. If you have any suggestions, drop me an email.

- [x] Add [Google style](http://google.github.io/styleguide/pyguide.html)
- [x] Add [Sphinx style](http://www.sphinx-doc.org/en/master/usage/restructuredtext/domains.html#info-field-lists)
- [ ] Scan for `Exceptions`
- [ ] Convert between styles
- [x] Add support for Type Hints ([PEP 484](https://www.python.org/dev/peps/pep-0484/))
- [x] Add lint support to show incomplete documentation
