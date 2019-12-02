# Str - Str Utilities for PHP

- str_starts($needles, $haystack)
- str_contains($needles, $haystack)
- str_ends($needles, $haystack)
- str_limit($value, $limit = 100, $end = '...') {
- str_snake_case($value, $delimiter = '\_')
- str_camel_case($value)
- str_studly_case($value)
- str_slug($title, $separator = '-')
- str_snake_case_safe($title, $separator = '_')
- str_json($str = '/', $returnDecoded = true, $asArray = false)

## Install

Install the latest version using [Composer](https://getcomposer.org/):

```
$ composer require vayes/str
```

Not available via composer yet.

## Usage

Import and use as it is:

```php
use function Vayes\Str\str_camel_case

$property = str_camel_case('snaked_case_string');
```

## License

[MIT license](LICENSE.md)