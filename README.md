# [![Swap](doc/logo.png)](https://github.com/florianv/swap)

> The exchange rates library for PHP

[![Build status][travis-image]][travis-url] [![Total Downloads][downloads-image]][downloads-url] [![Version][version-image]][version-url]

Swap allows you to retrieve currency exchange rates from various providers such as Google or Yahoo and optionally cache the results.
It is integrated to other libraries such as [`moneyphp/money`](https://github.com/moneyphp/money) and provides
a [Symfony Bundle](https://github.com/florianv/FlorianvSwapBundle) and a [Laravel Package](https://github.com/florianv/laravel-swap).

## Installation

```bash
$ composer require florianv/swap
```

## Documentation

The documentation can be found [here](https://github.com/florianv/swap/tree/readme/doc/doc.md).

## Providers

| Provider | Base Currency | Quote Currency |
|---------------------------------------------------------------------------|----------------------|----------------|
| [European Central Bank](http://www.ecb.europa.eu/home/html/index.en.html) | EUR | * |
| [Google Finance](http://www.google.com/finance) | * | * |
| [Open Exchange Rates](https://openexchangerates.org) | USD (free), * (paid) | * |
| [Xignite](https://www.xignite.com) | * | * |
| [Yahoo Finance](https://finance.yahoo.com) | * | * |
| [WebserviceX](http://www.webservicex.net/ws/default.aspx) | * | * |
| [National Bank of Romania](http://www.bnr.ro) | RON | * |
| [Central Bank of the Republic of Turkey](http://www.tcmb.gov.tr) | * | TRY |
| [Central Bank of the Czech Republic](http://www.cnb.cz) | * | CZK |
| [currencylayer](https://currencylayer.com) | USD (free), * (paid) | * |

## Integrations

- A Symfony Bundle [FlorianvSwapBundle](https://github.com/florianv/FlorianvSwapBundle)
- A Laravel Package [florianv/laravel-swap](https://github.com/florianv/laravel-swap)

## Credits

- [Florian Voutzinos](https://github.com/florianv)
- [All Contributors](https://github.com/florianv/swap/contributors)

## License

The MIT License (MIT). Please see [LICENSE](https://github.com/florianv/swap/blob/master/LICENSE) for more information.

[travis-url]: https://travis-ci.org/florianv/swap
[travis-image]: http://img.shields.io/travis/florianv/swap.svg?style=flat-square

[downloads-url]: https://packagist.org/packages/florianv/swap
[downloads-image]: https://img.shields.io/packagist/dt/florianv/swap.svg?style=flat-square

[version-url]: https://packagist.org/packages/florianv/swap
[version-image]: http://img.shields.io/packagist/v/florianv/swap.svg?style=flat-square
