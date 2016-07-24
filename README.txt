Low Level Virtual Machine (LLVM)
================================

This directory and its subdirectories contain source code for LLVM,
a toolkit for the construction of highly optimized compilers,
optimizers, and runtime environments.

LLVM is open source software. You may freely distribute it under the terms of
the license agreement found in LICENSE.txt.

Please see the documentation provided in docs/ for further
assistance with LLVM, and in particular docs/GettingStarted.rst for getting
started with LLVM and docs/README.txt for an overview of LLVM's
documentation setup.

If you are writing a package for LLVM, see docs/Packaging.rst for our
suggestions.

installation:
$ git clone https://github.com/8l/llvm2 llvm
$ mkdir llvm_build && cd llvm_build
$ cp ../llvm/run.sh . && ./run.sh
$ make && sudo make install

bug:
still in compilation process.
previous llvm_musl repo was svn-based. 
