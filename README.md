![3LM](./assets/img/logo.png) &nbsp;&nbsp; <span style="color: orange; font-size: 32px; vertical-align: middle;">3LM</span>

<img src="https://img.shields.io/github/license/knno/3lm" /> <img src="https://img.shields.io/github/repo-size/knno/3lm" /> <img src="https://img.shields.io/pypi/v/e3lm" /> 
[![Downloads](https://static.pepy.tech/personalized-badge/e3lm?period=total&units=abbreviation&left_color=grey&right_color=blue&left_text=Downloads)]()


Have fun while learning!

---

## So what is this exactly?

### This is an attempt at creating a markup language.

3LM is a structure language parsed in Python.

It is used for defining hierarchial objects, intended mainly to help write structured content fast and with ease.
Whether you are a scientist, a programmer or an educator, 3LM can be useful for you.

3LM is intended to be a language of use for an educational platform.

---

![Screenshot](./assets/img/screenshotto.jpg)

---

## Installation

The recommended way to install is using PyPI

### Installation through PyPI
Creating a virtual environment is very preferrable.

```bash
$ python -m venv venv
$ python -m pip install e3lm
```

### Installation from Github

Not preferrable, but it works too :)

```bash
$ pip install git+https://github.com/knno/3lm.git#egg=e3lm
```

## Configuration
```env
# Environment variables and their default values.

E3LM_TEMP_DIRECTORY="tmp"
```

## Usage

### Basic example

You can run these in your terminal to make sure it works:

```bash
$ e3lm --version
$ e3lm --help
$ e3lm -d code0
$ e3lm -d code0 -p json
$ e3lm examples/lesson1
```

More examples:

```bash
# Interpret an example.3lm file.
$ e3lm example.3lm

# Interpret demo code1 and generate graphviz dot file and view graph image.
$ e3lm -d code1 -p dot view

# Benchmarking 20 times the demo code0 for 6 measurements.
$ e3lm -d code0 -b 6 20
```

---

## Additional resources

Refer to the [Wiki](https://github.com/knno/3lm/wiki) to learn the language.

---

More possibilities... See [e3lm.todo](https://github.com/knno/3lm/blob/master/e3lm.todo)

---
