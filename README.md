# cfdm-docs
Archive store of built HTML documentation for old versions of cfdm

:warning: Note: this is archived documentation and not intended as the canonical
source for the latest version (though the archived copy should be identical to
the canonical one). **To view the latest version of the cfdm
documentation, always go to https://ncas-cms.github.io/cfdm/**.

### Background

This repository is designed to house built i.e. HTML-format files defining
the content of the built documentation for all
versions of the [cfdm](https://github.com/NCAS-CMS/cfdm) library.

Note that the contents of this directory, namely the built HTML documntation
for the older versions, used to live in the core cfdm repository (as
linked above) under `docs/`. They were moved out at version `1.10.0.3`.


### Structure

This repository is arranged such that the previous versions form the
top-level directories, named according to version (which is equal to
the corresponding branch name minus the inital `v` character), and the
content for the documentation at the given version is contained inside
the relevant directory.

### Updating

**For every cfdm release, the built documentation for the version that
has just been surpassed as the latest by a new release should be moved
here under its own (version name) top-level directory. It should not be
touched at all after that.**
