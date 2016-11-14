# phpdev-scoop-bucket
Basic Scoop bucket to manage installs needed for modern php development.

## [scoop](https://github.com/lukesampson/scoop)
`iex (new-object net.webclient).downloadstring('https://get.scoop.sh')`

## Setup
`scoop bucket add phpdev https://github.com/wrokred/phpdev-scoop-bucket`

### issues
Checks for PHP on local. If it's missing run:

`scoop install php`

## [Composer 1.2.2](https://getcomposer.org/)

`scoop install composer`

## [WP-CLI 0.25.0](http://wp-cli.org/)

`scoop install wp-cli`

## [Laravel Installer 1.3.4](https://laravel.com/)

`scoop install laravel` - requires composer
