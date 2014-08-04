emacs-minor-config
==================

Always project need user to report bug after testing minor config. This will help you test simply.

Design
======

## way 1 ##

* this repository is a collection of different minor-config files.

* architecture

        init_common.el -- for common setting. required by others.
        init_el-get.el -- for el-get.

## way 2 ##

* separate shell script load separate config file.
* generate config file dynamically.

## way 3 ##

* Emacs Lisp code file.


Functions
=========

* support package management
    * package
    * el-get
