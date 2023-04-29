# Object Mapper

Interface for [orisai/object-mapper](https://github.com/orisai/object-mapper) mapped objects

## Content

- [Setup](#setup)
- [Why](#why)

## Setup

Install with [Composer](https://getcomposer.org)

```sh
composer require orisai/object-mapper-contracts
```

## Why?

This package provides just interface `Orisai\ObjectMapper\MappedObject`. Thanks to that, it is possible to create a lib
with value objects which use object mapper as an optional dependency.

Annotations, attributes nor classes used in callbacks have to exist for value objects to be usable in use cases which do
not require object mapper.

For everything else, refer to [orisai/object-mapper](https://github.com/orisai/object-mapper) docs
