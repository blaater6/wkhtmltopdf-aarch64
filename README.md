wkhtmltopdf
================

!--- aarch64 build working for Amazon Linux ---!

This repository contains the static compiled binaries from the [wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf can be found there.

## Installation

_Hint_:
The version of the binary is equal to the git tag.
To install the latest version, use '0.12.4'.

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for _aarch64_ with:

    php composer.phar require blaater6/wkhtmltopdf-aarch64 "0.12.4"

The binary will then be located at:

    vendor/blaater6/wkhtmltopdf-aarch64/bin/wkhtmltopdf-aarch64

Also a symlink will be created in your configured bin/ folder, for example:

    vendor/bin/wkhtmltopdf-aarch64

### Usage

You can use the path constant to easily locate the binary in the PHP codebase: 

``` php
$path = \blaater6\WKHTMLToPDF\WKHTMLToPDF::PATH;
```

For realpath use following script

``` php
$realpath = realpath(\blaater6\WKHTMLToPDF\WKHTMLToPDF::PATH);
```
