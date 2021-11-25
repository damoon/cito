**Deprecated in favor of [https://github.com/turbine-kreuzberg/php-package-cache](https://github.com/turbine-kreuzberg/php-package-cache)**

# Cito

## installation
`composer global require damoon/cito`

## configuration
`CITO_DEBUG=1` enables debug output
`CITO_SERVER=http://127.0.0.1:8080` sets cito cache server

## testing
`rm -rf $COMPOSER_HOME/cache $HOME/.cache/composer/ vendor`
`CITO_DEBUG=1 composer require amphp/http-server`
