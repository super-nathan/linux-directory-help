linux-directory-help
====================

dirhelp - a command line tool to give information about the linux directory structures (FHS)

Dowloading/Installing:
- grab the appropriate binary for your system:
- [amd64 - 64 bit](https://github.com/jrenner/linux-directory-help/raw/master/bin/dirhelp-linux-amd64)
- [386 - 32 bit](https://github.com/jrenner/linux-directory-help/raw/master/bin/dirhelp-linux-386)
- [arm - Raspberry Pi, etc](https://github.com/jrenner/linux-directory-help/raw/master/bin/dirhelp-linux-arm)
- copy it somewhere in your PATH environment variable, I like to use ~/bin
- rename it to something easy to type like "dirhelp"
- MAKE SURE TO RUN "sudo chmod +x (filename)" so that the file is executable

How to use:
- run "dirhelp" in some typical directories like "/", "/media", "/var/log"
- run "dirhelp [path]" to get help on a specific path
- run "dirhelp -a" to see all the help strings

![Alt text](http://github.com/jrenner/linux-directory-help/raw/master/dirhelp.png "screenshot")

