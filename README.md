# (Temporary package) Migrate code to package: Configuration Engine

<!--
[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]
-->

Code to be migrated, from legacy PHP 5 code to modern PHP 7 code ([read more here](https://github.com/leoloso/PoP#codebase-migration)). Target package description:  Adds the configuration level to the component hierarchy, through which the data API can be extended into an application

## Install

Via Composer

``` bash
composer require getpop/migrate-component-model-configuration dev-master
```

**Note:** Your `composer.json` file must have the configuration below to accept minimum stability `"dev"` (there are no releases for PoP yet, and the code is installed directly from the `master` branch):

```javascript
{
    ...
    "minimum-stability": "dev",
    "prefer-stable": true,
    ...
}
```

<!--
## Usage

``` php
```
-->

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email leo@getpop.org instead of using the issue tracker.

## Credits

- [Leonardo Losoviz][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/getpop/component-model-configuration.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/getpop/component-model-configuration/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/getpop/component-model-configuration.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/getpop/component-model-configuration.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/getpop/component-model-configuration.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/getpop/component-model-configuration
[link-travis]: https://travis-ci.org/getpop/component-model-configuration
[link-scrutinizer]: https://scrutinizer-ci.com/g/getpop/component-model-configuration/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/getpop/component-model-configuration
[link-downloads]: https://packagist.org/packages/getpop/component-model-configuration
[link-author]: https://github.com/leoloso
[link-contributors]: ../../contributors
