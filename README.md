csvimp - a CSV Import Utility
=============================

[![Build Status on xtuple's master](https://travis-ci.org/xtuple/csvimp.svg?branch=master)](https://travis-ci.org/xtuple/csvimp)

The following points should be considered when working with 
CSVimp source code:

* Qt must be installed and working properly to successfully compile
  CSVimp.

* CSVimp must link with OpenRPT's "common" library. Therefore the
  code for openrpt must be checked out to build CSVImp. It should be
  stored in the same parent directory and should be compiled side-by-side.

The following describes the preferred method for compiling CSVimp:

1. Clone openrpt from GitHub
2. Clone csvimp from GitHub (save in same parent directory as used for xtuple module)
3. Compile openrpt
4. Compile csvimp
