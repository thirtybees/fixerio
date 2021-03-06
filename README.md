# Fixer.io Module

Provides currency exchange rates from fixer.io. Source: European Central Bank.

## Description

Note: this module went non-functional due to Fixer.io changing their API. Feature equal replacement is module [*ecbexchange* / *ECB Exchange Rate Services*](https://github.com/thirtybees/ecbexchange/releases).

This module regularly fetches exchange rates from the European Central Bank and applies them to the shop's currency exchange rates. Using it, your shop has always up to date exchange rates and can display prices in more than one currency without the risk of losses due to outdated currency conversion.

## License

This software is published under the [Academic Free License 3.0](https://opensource.org/licenses/afl-3.0.php)

## Contributing

thirty bees modules are Open Source extensions to the thirty bees e-commerce solution. Everyone is welcome and even encouraged to contribute with their own improvements.

For details, see [CONTRIBUTING.md](https://github.com/thirtybees/thirtybees/blob/1.0.x/CONTRIBUTING.md) in the thirty bees core repository.

## Packaging

To build a package for the thirty bees distribution machinery or suitable for importing it into a shop, run `tools/buildmodule.sh` of the thirty bees core repository from inside the module root directory.

For module development, one clones this repository into `modules/` of the shop, alongside the other modules. It should work fine without packaging.

## Roadmap

#### Short Term

* None currently.

#### Long Term

* None currently.
