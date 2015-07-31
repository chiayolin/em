em: Plaintext Manual Page Generator
========================

`em` outputs every man(1) page on your UNIX machine into plaintext files.

Usage 
-----

`cd` into the git repository, then run:

```sh
./bin/em
```

It might take about two and half minutes to export all the man pages into plaintext files.

After the program finishes running, you will find two new files have the prefix `em-`. 

```sh
$ ls -l
...
drwxr-xr-x     3 chiayo  staff    102 Dec 30 09:14 bin
drwxr-xr-x  1361 chiayo  staff  46274 Dec 30 09:14 em-883440000
-rw-r--r--     1 chiayo  staff    798 Dec 30 09:14 em-883440000.log
...
```
