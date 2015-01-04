# benkoder [![Build Status](https://travis-ci.org/integricho/benkoder.svg)](https://travis-ci.org/integricho/benkoder)

A Clojure library designed to perform Bencode encoding and decoding.

## Usage

    (use '[benkoder.encode])
    (bencode {:a 3})

or

    (use '[benkoder.decode])
    (bdecode "d1:ai3ee")

## License

Copyright © 2015 Andrean Franc

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
