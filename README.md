RESOLVE-Workspace
==============
[![License](https://img.shields.io/badge/license-BSD-blue.svg)](https://raw.githubusercontent.com/ClemsonRSRG/RESOLVE-Workspace/master/LICENSE.txt)

This is a collection of RESOLVE concepts, enhancements, realizations and theories used in conjunction with the [RESOLVE Compiler](https://github.com/ClemsonRSRG/RESOLVE). It also contains a Java implementation of the underlying low-level structure for the RESOLVE to Java translations. These files will be bundled with the translated files when creating an runnable jar file.

All RESOLVE library files are located inside the `Main` folder and is separated into `Concepts`, `Facilities` and `Math_Units`. Each concept has its own folder where you could have arbitrarily many concept realizations and/or enhancement extensions. For the different facilities, we have separated them into different categories for organizational purposes. All existing mathematical theories can be found inside the `Math_Units` folder.

Note that most of the concepts, implementations and theories appearing in this repository exist in a variety of states ranging from somewhat mature, to very early, unfinished (and unverified!) efforts *that might or might not currently work with the latest version of the compiler*. Each library additionally will contain various pieces of documentation that give anyone interested information on mathematical model, specifications, operations, implementation(s), etc.

## What is RESOLVE?

RESOLVE (REusable SOftware Language with VErification) is a programming and specification language designed for verifying correctness of object oriented programs.

The RESOLVE language is designed from the ground up to facilitate *mathematical reasoning*. As such, the language provides syntactic slots for assertions such as pre-post conditions that are capable of abstractly describing a program's intended behavior. In writing these assertions, users are free to draw from from a variety of pre-existing and user-defined mathematical theories containing fundamental axioms, definitions, and results necessary/useful in establishing program correctness.

All phases of the verification process spanning verification condition (VC) generation to proving are performed in-house, while RESOLVE programs are translated to Java and run on the JVM.

## Authors and major contributors

The creation and continual evolution of the RESOLVE language is owed to an ongoing joint effort between Clemson University, The Ohio State University, and countless educators and researchers from a variety of [other](https://www.cs.clemson.edu/resolve/about.html) institutions.

Developers of this particular test/working-iteration of the `RESOLVE Compiler` and its associated library files include:

* [RESOLVE Software Research Group (RSRG)](https://www.cs.clemson.edu/resolve/) - School of Computing, Clemson University

## Copyright and license

Copyright © 2023, [RESOLVE Software Research Group (RSRG)](https://www.cs.clemson.edu/resolve/). All rights reserved. The use and distribution terms for this software are covered by the BSD 3-clause license which can be found in the file `LICENSE.txt` at the root of this repository. By using this software in any fashion, you are agreeing to be bound by the terms of this license. You must not remove this notice, or any other, from this software.
