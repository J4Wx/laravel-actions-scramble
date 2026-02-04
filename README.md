# Laravel Actions <-> Scramble

If you are using [laravel actions](https://laravelactions.com/) as controllers, this add-on enables parsing of those routes in the automatic doc-generation that [scramble](https://scramble.dedoc.co/) does.

```sh
composer require j4wx/laravel-actions-scramble
```

Just add the class to the `extensions` array in the `config/scramble.php` file:

```php
    ...
    'extensions' => [
        \J4Wx\LaravelActionsScramble\LaravelActionsExtension::class
    ],
```
