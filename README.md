HEKA PatchMaster Data Reader
============================

Luke Campagnola <luke.campagnola@gmail.com>
2015

This is a simple pure-python reader for .dat bundle files generated by HEKA 
PatchMaster. It provides access to trace data and the metadata
hierarchy in the embedded .pul file. 

Heka_reader is based on similar code provided with StimFit; however, that
implementation was written in C++ and is difficult to compile on some platforms. 


Requirements
============

* Python 2.7 or 3+
* NumPy

The included browser script also requires PyQtGraph.


Instructions
============

This module has no installation scripts; simply copy `heka_reader.py` into your
project. See the included `browser.py` for an example of how to load files and 
read data / metadata.
