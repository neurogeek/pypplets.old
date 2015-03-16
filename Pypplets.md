Pypplets main

# Introduction #

Pypplets is a Python-based Applets Framework for Mozilla-based Browsers. Pypplets is a Mozilla plugin developed in C++ that uses the CPython API and Mozillas Graphical Toolkit (eg. GTK+) and it allows developers to write Python applications (with a template, much as Java® Applets ) that can then be embedded into the browser.

# Project Status #

The initial commit was made today (09/09/2009)

The status is pre-alpha, that means not much is tested so you
**run this code under your own risk**.

The project can be built using SCons, just run scons in the project
folder and it will generate a libpypplets.so. You may place this file
under ~/.mozilla/plugins to make it available to your browser.

Currently, it only executes Python scripts, so not many exciting things
will currently happen. I will post soon enough a test page with a Pypplet
embedded.