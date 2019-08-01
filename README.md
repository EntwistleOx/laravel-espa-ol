# Agregando paquete de idioma español para Laravel ^5:

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
