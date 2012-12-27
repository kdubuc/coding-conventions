# [Coding Conventions](https://github.com/kdubuc/coding-conventions/blob/master/README.md) - CC5 : Databases

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in [RFC 2119][].

[RFC 2119]: http://www.ietf.org/rfc/rfc2119.txt
[PSR-0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md

## General

* Tables MUST BE lowercase and plural e.g. items, cars.
* The tables's storage engine MUST BE InnoDB.
* The tables's collation MUST BE utf8_general_ci.
