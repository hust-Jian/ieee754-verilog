IEEE 754 - Adder/Subtractor
===========================

Written in verilog for compilers/simulators:

* `iverilog` Open Source Verilog simulator
    See: `make_windows.sh`

* `VCS` (Verilog Compiled Simulator)

Language
========

Most of files are written in verilog. Exception is file `src/ieee.vs`. This file is written in new
experimental language [VerilogScript](http://github.com/emiraga/verilogscript). `src/ieee.vs` is translated
by VerilogScript compiler into a file `src/ieee.v`.

File `ieee/ieee_adder.v` is automatically generated by two files: `src/generate.py` and `src/config.py`.
Purpose of automated generator is to make creation of pipeline easier.

Verification
============
    Succeded 554941 test, Failed 29871 tests
    Sucess: 94.89%

Contact
=======

E-mail: [emiraga@gmail.com](mailto:emiraga@gmail.com)
