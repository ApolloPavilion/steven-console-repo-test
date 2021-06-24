# Caesar Cipher

People have always been up to tomfoolery and shenanigans. Shenanigans don't work unless you can keep them hidden. In this assignment, you'll be building a [Caesar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

## Examples

Create a file named `caesar.c`. We'll compile it to a binary named `caesar`.

Running `./caesar 1` will wait for standard in. If we give it `a` it should output `Ciphertext: b` followed by a new line.
This is an example of our program encrypting "a" as "b" using 1 as its key.

It should also:
1. encrypt "barfoo" as "yxocll" using 23 as its key
2. encrypt "BARFOO" as "EDUIRR" using 3 as its key
3. encrypt "BaRFoo" as "FeVJss" using 4 as its key
4. encrypt "barfoo" as "onesbb" using 65 as its key
5. encrypt "world, say hello!" as "iadxp, emk tqxxa!" using 12 as its key
6. errors out if no argument is passed
