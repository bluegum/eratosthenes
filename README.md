Eratosthenes
============

The sieve of eratosthenes implemented in Postscript programming language



Contributing and tribute to the sieve of eratosthenes algorithm and the
Postscript programming language, This little piece of code generate an
early range of prime number.

This code is in public domain.


Usage:
This code is intended to be used on linux boxes and with interactive
Postscript interpreters.

1. Download Ghostscript.

2. Download source code.

3. run:
user@machine>gs -sDEVICE=nullpage sieve-of-eratosthenes.ps

You type in the top of the range, 60000 for
Ghostscript, as any larger number will cause some mystic memory error,
and you will have an array of all the primes within the range printed out in terminal.
