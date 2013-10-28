fextract - A Mathematical Functional Form Extractor
(c) 2013 - Chris Kennelly (chris@ckennelly.com)

Overview
========

Numerical algorithm implementations frequently unintentionally obfuscate the mathematical expression they convey to cursory examination.  Extracting this information from binary code allows implementations to be validated and the impact of compiler optimizations to be assessed, especially on floating point operations.  

Limitations
===========

* fextract cannot support arbitrary levels of recursion.
