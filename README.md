# Agregando paquete de idioma español en Laravel 5.8

```
$| composer require laraveles/spanish
$| php artisan vendor:publish --tag=lang
```

En el archivo config/app.php, modificar:

```
'locale' => 'en'
```

Por:
```
'locale'  => 'es'
```
