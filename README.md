# phpdev-scoop-bucket
Basic Scoop bucket to manage installs needed for modern php development.

## [Scoop](https://github.com/lukesampson/scoop)
``` powershell
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
```

## Setup
``` powershell
scoop bucket add phpdev https://github.com/wrokred/phpdev-scoop-bucket
```

### issues
Checks for PHP on local. If it's missing run:
``` powershell
scoop install php
```

## [Composer](https://getcomposer.org/) 1.2.2

``` powershell
scoop install composer
```
- requires php

## [WP-CLI](http://wp-cli.org/) 0.25.0

``` powershell
scoop install wp-cli
```
- requires php

## [Laravel Installer](https://laravel.com/) 1.3.4

``` powershell
scoop install laravel
```
- Includes artisan alias
- requires composer
- requires php
