# Laravel Economic REST wrapper

------

## Working on a new version

Tested, easier to use and with all REST endpoints available.

*Also, framework agnostic w/ Laravel Facade + config for the Laravel users.*

------

## Installation

1. Require using composer
````
composer require lasserafn/laravel-economic
````

2. Add the EconomicServiceProvider to your ````config/app.php```` providers array.
````
'providers' => [
    \LasseRafn\Economic\EconomicServiceProvider::class,
]
````
3. Copy the package config to your local config with the publish command: 
```
php artisan vendor:publish --provider="LasseRafn\Economic\EconomicServiceProvider"
```
## [Contributors](https://github.com/LasseRafn/laravel-economic/graphs/contributors)
