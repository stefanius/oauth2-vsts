# Visual Studio Team Services (VSTS) and Team Foundation Server (TFS) Provider for OAuth 2.0 Client
[![Latest Version](https://img.shields.io/github/release/jeylabs/oauth2-vsts.svg?style=flat-square)](https://github.com/jeylabs/oauth2-vsts/releases)
[![Total Downloads](https://img.shields.io/packagist/dt/jeylabs/oauth2-vsts.svg?style=flat-square)](https://packagist.org/packages/jeylabs/oauth2-vsts)
[![Software License](https://img.shields.io/packagist/l/jeylabs/oauth2-vsts.svg?style=flat-square)](LICENSE.md)

This package provides [Visual Studio Team Services (VSTS) and Team Foundation Server (TFS)](https://docs.microsoft.com/en-us/vsts/integrate/) OAuth 2.0 support for the PHP League's [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Tests](#tests)
- [Changelog](#changelog)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## Installation

To install the client you need to require the package using composer:

	$ composer require jeylabs/oauth2-vsts

Use composer's autoload:

```php
require __DIR__.'/../vendor/autoload.php';
```

You're all set up now!

## Usage

Usage is the same as The League's OAuth client, using `\Jeylabs\OAuth2\Client\Provider\VSTS` as the provider.

## Examples

## Tests

The package contains integration tests. You can run them using PHPUnit.

    $ vendor/bin/phpunit

## Changelog

Refer to [CHANGELOG](CHANGELOG.md) for more information.

## Contributing

Refer to [CONTRIBUTING](CONTRIBUTING.md) for contributing details.

## Credits

* **Thijs Kok** - *Lead developer* - [ThijsKok](https://github.com/thijskok)
* **Stephan Grootveld** - *Developer* - [Stefanius](https://github.com/stefanius)
* **Frank Keulen** - *Developer* - [FrankIsGek](https://github.com/frankisgek)

## License

The MIT License (MIT). Refer to the [License](LICENSE.md) for more information.