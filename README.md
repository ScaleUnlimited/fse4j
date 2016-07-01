# fse4j
Java port of FiniteStateEntropy project in GitHub (https://github.com/Cyan4973/FiniteStateEntropy)

From the upstream project...

>__FSE__ is a new kind of [Entropy encoder](http://en.wikipedia.org/wiki/Entropy_encoding), based on [ANS theory, from Jarek Duda](http://arxiv.org/abs/1311.2540), achieving precise compression accuracy (like [Arithmetic coding](http://en.wikipedia.org/wiki/Arithmetic_coding)) at much higher speeds.

This is a very specific port, though - it provides support for compressing/decompressing Java shorts, and assumes a fixed, pre-calculated table for compression & decompression.


