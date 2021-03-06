# FortranFiles.jl

A Julia package for reading and writing Fortran unformatted (i.e. binary) files.


## Features ##

Currently the following features are implemented and working:

* Sequential Access mode
  * 4-byte record markers, with subrecord support (allowing records larger than 2 GiB)
  * 8-byte record markers (used by early versions of gfortran)
* Most standard Fortran datatypes, including arrays and strings
* "Inhomogeneous" records, i.e. records made from multiple different datatypes

The following features are not (yet) supported:

* Direct Access mode
* Derived Type I/O
* Equivalents of BACKSPACE and ENDFILE


## Documentation

```@contents
Pages = [
   "files.md",
   "types.md",
   "read.md",
   "write.md",
   "tests.md",
   "theindex.md"
]
```

