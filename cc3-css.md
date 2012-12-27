# [Coding Conventions](https://github.com/kdubuc/coding-conventions/blob/master/README.md) - CC3 : CSS

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in [RFC 2119][].

[RFC 2119]: http://www.ietf.org/rfc/rfc2119.txt
[PSR-0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md

## General

* Put spaces after : in property declarations.
* Put spaces before { in rule declarations.
* Use hex color codes #000 unless using rgba.
* Use // for comment blocks (instead of /* */).

Example :

````css
.example {
  color: #555;
  border: 1px solid #000;
}
````

## Device-agnostic ans mobile-first

Don’t define your breakpoints according to some device, define your breakpoints when your design breaks.

If your application must be mobile, you MUST think mobile-first. You start from the smallest possible space, and built from there.

## OOCSS

You MUST use the [OOCSS principle](http://www.stubbornella.org/content/category/general/geek/css/oocss-css-geek-general/).

## Pixels vs. Ems / Rems

You SHOULD use Ems / Rems / percents instead of pixels.

## LESS

You SHOULD use a dynamic stylesheet language. [LESS](http://lesscss.org/) is recommended.

## Framework CSS

It's highly recommended to use a framework. [Twitter Bootstrap](http://twitter.github.com/bootstrap/) is recommended.
