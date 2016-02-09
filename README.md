# aes
Almost 10 years old code implementing AES128 that needs fixing.

## compilation
cc -std=c99 aes.c -o aes

## running
cat input.hex |./aes |hexdump

## testing
cat input.hex |./aes |hexdump | diff output.txt  -
