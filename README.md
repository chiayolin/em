em: Plaintext Manual Page Generator
========================

`em` outputs every man(1) page on your Unix machine into plaintext files.

Usage 
-----

`cd` into the git repository, then run:

```sh
./bin/em
```

It takes about two and half minutes to export all the man pages into plaintext files.

After the program finishes running, you will find two new files with the prefix `em-`: 

```sh
$ ls -l
...
drwxr-xr-x     3 foo  bar    102 Dec 30 09:14 bin
drwxr-xr-x  1361 foo  bar  46274 Dec 30 09:14 em-883440000
-rw-r--r--     1 foo  bar    798 Dec 30 09:14 em-883440000.log
...
```

One of the files is the directory where every plaintext version of man(1) page is exported. And obviously, the one ended with the surfix `.log` is the log file. Note that the number followed by `em-` is the [Unix time](https://en.wikipedia.org/wiki/Unix_time). The reason of putting Unix time stamp after `em-` is to prevent duplicate directories within the same directory. 

License
-------
The code is licensed under the [GNU General Public License 3.0](https://raw.githubusercontent.com/chiayolin/em/master/LICENSE)
