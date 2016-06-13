# OpenGraph

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

OpenGraph
Open Graph page scrapper.

## Install

Via Composer

``` bash
$ composer require jworksuk/opengraph
```

## Usage

``` php
$opengraph = new JWorksUK\OpenGraph\OpenGraph::fetch(
    'http://www.thingsofmyinterest.com/2013/02/urbance-trailer/'
);
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

HTML blank exception
No tags exception

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email me@jworksuk.com instead of using the issue tracker.

## Credits

- [Jesse James][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/jworksuk/opengraph.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/jworksuk/opengraph/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/jworksuk/opengraph.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/jworksuk/opengraph.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/jworksuk/opengraph.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/jworksuk/opengraph
[link-travis]: https://travis-ci.org/jworksuk/opengraph
[link-scrutinizer]: https://scrutinizer-ci.com/g/jworksuk/opengraph/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/jworksuk/opengraph
[link-downloads]: https://packagist.org/packages/jworksuk/opengraph
[link-author]: https://github.com/jworksuk
[link-contributors]: ../../contributors