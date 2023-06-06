# Valu WordPress PHP Code Sniffer ruleset

## Install

`composer require valu/wp-php-ruleset`

## Configure 

Add `phpcs.xml` with

```xml
<?xml version="1.0"?>
<ruleset xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" name="Custom" xsi:noNamespaceSchemaLocation="https://raw.githubusercontent.com/squizlabs/PHP_CodeSniffer/master/phpcs.xsd">
    <rule ref="Valu-WP-Rules"/>
</ruleset>
```

and run 

```
./vendor/bin/phpcs src
```
