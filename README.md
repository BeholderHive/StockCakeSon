# Stock plugin for CakePHP

## Installation

You can install this plugin into your CakePHP application using [composer](https://getcomposer.org).

The recommended way to install composer packages is:

```
composer require beholderhive/stock-cake-son
```

Update your 'config/bootstrap.php'.

```
Plugin::load('Stock',  ['bootstrap' => false, 'routes' => true]);
```

Run migrations

```
bin/cake migrations migrate --plugin Stock
```
