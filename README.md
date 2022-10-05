wkhtmltopdf-windows
================
Using latest version of wkhtmltopdf 0.12.6 (05 October 2022)
This Repo is just update from this repo https://github.com/wemersonjanuario/wkhtmltopdf-windows

[wkhtmltopdf project](http://wkhtmltopdf.org/).
More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

Binaries for __Linux i386__, also installable with composer, can be found here: [github.com/h4cc/wkhtmltopdf-i386](https://github.com/h4cc/wkhtmltopdf-i386)

Binaries for __Linux amd64__, also installable with composer, can be found here: [github.com/h4cc/wkhtmltopdf-amd64](https://github.com/h4cc/wkhtmltopdf-amd64)

## Installation

_Hint_:
The version of the binary is equal to the git tag.

In case this package does _not_ work on your system, try installing the matching system packages from here: [http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html).

### Packagist

This package can be found on [Packagist](http://packagist.org) and installed with [Composer](https://getcomposer.org/).

Require the package for Windows with:
    composer require mikysetiawan/wkhtmltopdf-windows

The binaries will then be located at:
    vendor/mikysetiawan/wkhtmltopdf-windows/bin/wkhtmltopdf-windows

Also a symlink will be created in your configured bin/ folder, for example:
    vendor/bin/32bit/wkhtmltopdf.exe.bat and vendor/bin/64bit/wkhtmltopdf.exe.bat