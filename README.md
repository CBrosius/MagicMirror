# MagicMirror
MultiArch Testbuild for MagicMirror

When I started to test MagicMirror with the original Docker-Image (https://hub.docker.com/r/karsten13/magicmirror) it did not work for me on my Raspberry PI4 because it states 'Exec Format error'

So I decided to try MultiArch-Compiling via Docker-Hub by myself.

After the compiling worked, I changed the initial Config a little bit, so that you will get a working Server-Only Container right out of the box that you can access with just a browser.

I can only test arm32 and amd64 by myself, so arm64 is compiled but not tested.

Finally I added a german sample-config-file because that is what I am trying to use by myself.

If you have any comments, please let me know via my Blog (https://christian.flixblog.de/2019/12/26/magicmirror/)

Latest Update: 2021/5/11
