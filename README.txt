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
compilation done.
seems to comile hello.c ;D

$ clang --version
clang version 3.9.0 (http://llvm.org/git/clang.git 7b869db6dd2793d9d004b8d210f67d7c5290dcc1) (http://llvm.org/git/llvm.git 080fa5779162278cba5d14dfebdb64993e3a2a84)
Target: x86_64-alpine-linux-musl
Thread model: posix
InstalledDir: /usr/bin

$ clang hello.c && ./a.out
hello musl llvm!
$

