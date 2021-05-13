# N-Queens - Challenge #1
First challenge in the code golf series.
# Compilation
Even though the compiled binary is included, you can use the included `MakeFile` to compile the binary.
```console
foo@bar:~$ make
```
Or directly use `cc`
```console
foo@bar:~$ cc -Wall -g -O0 nqueen.c -o nqueen
```
`-O0` option might be required due to a `return` trick (`x=!!x` instead of `return x`).