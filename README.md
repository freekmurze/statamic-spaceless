# Spaceless - Remove whitespaces between HTML tags.

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![SensioLabsInsight](https://img.shields.io/sensiolabs/i/32bfd56f-d4b3-4ec4-b988-a19da523c276.svg?style=flat-square)](https://insight.sensiolabs.com/projects/32bfd56f-d4b3-4ec4-b988-a19da523c276)
[![Quality Score](https://img.shields.io/scrutinizer/g/marbles/statamic-addon-starter.svg?style=flat-square)](https://scrutinizer-ci.com/g/marbles/statamic-addon-starter)
[![StyleCI](https://styleci.io/repos/76184586/shield?branch=master)](https://styleci.io/repos/76184586)

## Installation

Download or clone the repository, rename the folder to `Spaceless` then copy the folder to your site's `Addons` directory, then refresh the add-ons to install the dependencies.

``` bash
php please addons:refresh
```

## Usage

Use the tags around the html where you want whitespace removed

```
 {{ spaceless }}
      <div>
          <strong>foo</strong>
      </div>
 {{ /spaceless }}
```
 
 The output will be
 
 ```
 <div><strong>foo</strong></div>
 ```
 
## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email rias@marbles.be instead of using the issue tracker.

## Credits

- [Rias Van der Veken](https://github.com/rias500)
- [All Contributors](../../contributors)

## About Marbles
Marbles is a digital communication agency based in Antwerp, Belgium. Learn more about us [on our website](https://www.marbles.be).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
