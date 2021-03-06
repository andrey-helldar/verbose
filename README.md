# Verbose

Displaying verbose messages

[![Stable Version][badge_stable]][link_packagist]
[![Unstable Version][badge_unstable]][link_packagist]
[![Total Downloads][badge_downloads]][link_packagist]
[![License][badge_license]][link_license]

## Table of contents

* [Installation](#installation)
* [Using](#using)

## Installation

To get the latest version of `Verbose`, simply require the project using [Composer](https://getcomposer.org):

```bash
$ composer require andrey-helldar/verbose
```

Or manually update `require` block of `composer.json` and run `composer update`.

```json
{
    "require": {
        "andrey-helldar/verbose": "^1.0"
    }
}
```

## Using

```php
use Helldar\Verbose\Services\Logger;
use Helldar\Verbose\Facades\Log;

Logger::io($this->getIO());

Log::write('foo');
Log::write('bar');
Log::write('baz');
```

[badge_downloads]:      https://img.shields.io/packagist/dt/andrey-helldar/verbose.svg?style=flat-square

[badge_license]:        https://img.shields.io/packagist/l/andrey-helldar/verbose.svg?style=flat-square

[badge_stable]:         https://img.shields.io/github/v/release/andrey-helldar/verbose?label=stable&style=flat-square

[badge_unstable]:       https://img.shields.io/badge/unstable-dev--main-orange?style=flat-square

[link_license]:         LICENSE

[link_packagist]:       https://packagist.org/packages/andrey-helldar/verbose
