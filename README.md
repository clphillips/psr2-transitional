## PSR-2 Transitional Ruleset for PHPCS

This ruleset for [PHPCS](https://github.com/squizlabs/PHP_CodeSniffer), processes all [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) rulesets with the sole exception of **namespace** declarations. This allows you to ensure you are adhering to PSR-2 while transitioning from non-namespaced classes.

### Usage

Install PHPCS:

```sh
composer global require "squizlabs/php_codesniffer=*"
```

Run for your project or file:

```sh
phpcs --standard=./ruleset.xml /path/to/your/source
```
