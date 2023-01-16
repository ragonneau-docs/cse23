# Presentation for CSE23

![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ragonneau/cse23/build.yml?logo=github&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/ragonneau/cse23?logo=github&style=for-the-badge)

## Getting started

To generate the PDF version of the presentation, you first need to install [latexmk](https://ctan.org/pkg/latexmk?lang=en) v4.51 or later.
Next, clone this repository, and load the bibliography:

```bash
git submodule update --init
```

The PDF file can be generated with:

```bash
make
```
