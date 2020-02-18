## Laravel101
Permulaan untuk coding boilerplate

##### Packages

[PhpStorm IDE Helpher Laravel](https://github.com/barryvdh/laravel-ide-helper)

##### Code Helper
_PhpStorm idehelper_
```json
 "post-update-cmd": [
            "@php artisan clear-compiled",
            "@php artisan cache:clear",
            "@php artisan config:clear ",
            "@php artisan view:clear",
            "@php artisan route:clear",
            "@php artisan optimize:clear",
            "@php artisan ide-helper:generate",
            "@php artisan ide-helper:meta"
        ]
```
_Web Route(cannot go declaration)_
```php
//class Route extends Illuminate\Support\Facades\Route {}
use Illuminate\Support\Facades\Route;
```