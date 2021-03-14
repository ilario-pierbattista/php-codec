# Php-codec

Php-codec is a partial porting of [io-ts](https://github.com/gcanti/io-ts) in PHP.

[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%207.2-8892BF.svg)](https://php.net/)

[![CI](https://github.com/ilario-pierbattista/php-codec/actions/workflows/ci.yaml/badge.svg?branch=master&event=push)](https://github.com/ilario-pierbattista/php-codec/actions/workflows/ci.yaml)
[![Static analysis](https://github.com/ilario-pierbattista/php-codec/actions/workflows/static-analysis.yaml/badge.svg?branch=master&event=push)](https://github.com/ilario-pierbattista/php-codec/actions/workflows/static-analysis.yaml)
[![codecov](https://codecov.io/gh/ilario-pierbattista/php-codec/branch/master/graph/badge.svg?token=HP4OFEEPY6)](https://codecov.io/gh/ilario-pierbattista/php-codec)

## Installation

    composer require pybatt/php-codec

## Types and combinators

All the implemented codecs and combinators are exposed through methods of the class `Pybatt\Codec\Codecs`.

| Typescript Type | PHP Type | Codec | 
| --- | --- | --- |
| `unknown` | `mixed` | TODO |
| `null` | `null` | `Codecs::null()` |
| `bool` | `bool` | `Codecs::bool()` |
| `number` | `int` | `Codecs::int()` |
| `number` | `float` | `Codecs::float()` |
| `string` | `string` | `Codecs::string()` |
| `'s'` | litteral of `string` | `Codecs::litteral('s')` |
