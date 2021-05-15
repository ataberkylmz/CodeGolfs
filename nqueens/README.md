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
# Usage
For a board sized NxN, pass N as the first command line argument like follows:
```console
foo@bar:~$ ./nqueens N
```
Where N is the number of Queens and the length of the board, e.g:
```console
foo@bar:~$ ./nqueens 4
```
```console
foo@bar:~$ ./nqueens 8
```
```console
foo@bar:~$ ./nqueens 14
```
