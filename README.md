uit-thesis [![Build Status](https://magnum.travis-ci.com/egraff/uit-thesis.svg?token=TSQTyShVBGYYU4qnLNR9&branch=master)](https://magnum.travis-ci.com/egraff/uit-thesis)
==========

LaTeX document class for writing theses

How to install?
--
Simply clone with
```
git clone --recursive https://github.com/egraff/uit-thesis.git
```
and then run ``make install``.

If you're running Windows, and don't have a POSIX-like environment installed, you could try to use the [Net Installer](https://github.com/egraff/uit-thesis-installer/raw/master/uit-thesis-install.exe) instead.


It won't compile!
--
Try updating your LaTeX installation. If you use MiKTeX, also try running one or several of the following commands in a *standard* command line (cmd.exe):
```
texhash
initexmf --admin -u
initexmf --admin --mkmaps
initexmf -u
initexmf --mkmaps
```

## Licence
The contents of this GitHub repository is licensed under the CC BY-NC-ND licence.
Among other things, this means that you are not allowed to redistribute any derivatives of the contents of this repository.
This is to prevent ending up with several different, specialized versions of the thesis template floating around.
Instead, we want all improvements or new functionality to be made available from one place—this repository—thus making it easier for everyone to benefit from such changes.

Note that we do NOT impose any restrictions on the licensing or redistribution of your thesis—either in its source code form (excluding any parts of the UiT Thesis LaTeX template) or as a compiled document (i.e. PDF file).

We also require you to add an attribution to all documents that use the UiT Thesis LaTeX template.
By default, the template automatically adds a small attribution notice at the bottom of the first verso page of any document using it.
Note that although it is easy to disable this, you are not allowed to do so, unless special permission has been granted.


### Does this mean that I'm not allowed to fork this repository?

No, in accordance with the GitHub Terms of Service, you are allowed to fork this repository.
You are allowed to make changes to your fork to produce pull requests against this repository (i.e. for improvements or new functionality).

However, to the extent permittable by the GitHub Terms of Service, we do not allow you to fork this repository as a means of redistributing a derivative of the UiT Thesis LaTeX template.
