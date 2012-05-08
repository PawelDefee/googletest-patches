googletest-patches
==================

Patches containing new functionality for Google&#39;s unit test framework.


google-protocol-buffers-patches
===============================

This repository contains patches for Google&#39;s unit test framework. For more information on Google Test unit test framework, see http://code.google.com/p/googletest/.

To use any of the patches, simply apply them on top of a plain Google Test installation with the UNIX 'patch' command.

gtest-1.6.0-virtual-method-crash-fix.diff
-------------------------------------

This patch fixes a crash in GoogleTest internal unit tests that occur due to a bug in code generation by the optimizing GCC compiler.


