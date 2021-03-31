# Testing zlib-ng


1. Install zlib-ng https://github.com/zlib-ng/zlib-ng
2. Compile the project `gcc zpipe.c -l z-ng -o zpipe`
3. A boring test :  `echo test | ./zpipe | ./zpipe -d | cat`

Credit to https://www.zlib.net/zlib_how.html
