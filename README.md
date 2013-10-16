Card generator
=============

A node.js library to generate and validate credit card numbers.

The card numbers are valid with respect to the Luhn algorithm (Mod 10 test).
https://en.wikipedia.org/wiki/Luhn_algorithm

Specific details can be set on the fly to allow different card types generation.

Interface
-----
```js
cardNumber([Scheme], [numberOfCards], [pseudoRandomFunction]);
```
pseudoRandomFunction must supply random numbers between 0 to 1.
Use this in conjunction with a seeded random number generator to reproduce test data.

Contributing
------------
All meaningful contributions are welcome. 
Tests even more.

LICENSE
-------
GNU GPL
https://gnu.org/licenses/gpl.html

Original code was forked from https://github.com/ExxKA/credit-card-generator

That was forked from https://github.com/grahamking/darkcoding-credit-card
