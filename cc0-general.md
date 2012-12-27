# [Coding Conventions](https://github.com/kdubuc/coding-conventions/blob/master/README.md) - CC0 : General 

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in [RFC 2119][].

[RFC 2119]: http://www.ietf.org/rfc/rfc2119.txt
[PSR-0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[PSR-1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md

## Systems development life-cycle

### Versionning

The versionning and revision control MUST BE used in all projects. Git is recommended.

### Continuous integration

Continuous integration should be implemented for all projects. Code committed to revision control should be validated against international standards and best practice. If the code passes validation then it should be processed for deployment. Deployment process should include concatenation and minification. Travis CI is recommended.

## Coding style and structure

### Overview

The code must be human comprehensive and MUST BE follow the guidelines describes in the CC0, CC1, CC2 and CC3.

Code MUST use 4 spaces for indenting, not tabs.

> N.b.: Using only spaces, and not mixing spaces with tabs, helps to avoid
> problems with diffs, patches, history, and annotations. The use of spaces
> also makes it easy to insert fine-grained sub-indentation for inter-line 
> alignment.

There MUST NOT be a hard limit on line length; the soft limit MUST be 120 characters; lines SHOULD be 80 characters or less.

### File paths

File paths MUST BE absolute. Avoid the relative file paths.

### File encoding

Files MUST BE only UTF-8 without BOM.
