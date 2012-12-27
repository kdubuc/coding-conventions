# [Coding Conventions](https://github.com/kdubuc/coding-conventions/blob/master/README.md) - CC2 : Javascript

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in [RFC 2119][].

[RFC 2119]: http://www.ietf.org/rfc/rfc2119.txt
[PSR-0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md

## CoffeeScript

### What is Coffee Script ?

CoffeeScript is a programming language that transcompiles to JavaScript. The language adds syntactic sugar inspired by Ruby, Python and Haskell to enhance JavaScript's brevity and readability, and add more sophisticated features like list comprehension and pattern matching. CoffeeScript compiles predictably to JavaScript and programs can be written with less code, typically 1/3 fewer lines, with no effect on runtime performance. ([learn more about Coffee Script](http://en.wikipedia.org/wiki/CoffeeScript))

That's why you SHOULD use Coffee Script for Javascript code.

### Coding style

You MUST follow these rules :

* Always use camelCase, never underscores.
* Use implicit parentheses when possible.
* Any top level objects should be namespaced under the GitHub namespace.
* Don't ever use $.get or $.post. Instead use $.ajax and provide both a success * handler and an error handler.
* Use $.fn.on instead of $.fn.bind, $.fn.delegate and $.fn.live.

If you want more details, read the [CoffeeScript Style Guide](https://github.com/polarmobile/coffeescript-style-guide/blob/master/README.md) writed by [Polar Mobile](https://github.com/polarmobile).

## Existing Javascript

* Avoid adding new .js files.
* Do your best to never use a semicolon. This means avoiding them at line breaks and avoiding multi-statement lines. For more info, read [Mislav's blog post](http://mislav.uniqpath.com/2010/05/semicolons/).
