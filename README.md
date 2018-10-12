Stubs for PHP AMQP Binding Library
====

Forked from https://github.com/pdezwart/php-amqp

Provides only stubs.

Useful for test environments where ext-amqp is not installed and should be mocked.


## Usage

Add to composer.json:
```
"repositories" : [
    { "type": "vcs", "url":  "https://github.com/timostamm/php-amqp-stubs/" }
],
```

Require dev:
```
composer require --dev timostamm/php-amqp-stubs:dev-master
```

Include - for example in an autoload file for phpunit:
```php
<?php
require_once __DIR__ . '/../vendor/timostamm/php-amqp-stubs/stubs.php';
return require __DIR__ . '/../vendor/autoload.php';
```
