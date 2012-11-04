caa-dev-apps--cef-val
=====================

A cef (Cluster Exchange Format) validator.


A small project to parse and validate cef files.
The initial idea is to reuse some of the lua code that was used in various
sub-projects on the google hosted caa-dev-apps project.


Command line usage:
===================

./app-name -I /include/path/ceh-heaaders-#1 -I /include/path/ceh-heaaders-#2 ... /path-to-cef-filename.cef

TODO:
=====
 - parse header data of main cef file
 - parse referenced ceh files
 - check/validate header meta data
    - correct names
    - data types
    - more to follow
 - read data records
    - check timestamps
    - data types
    - fill-vals
    - more