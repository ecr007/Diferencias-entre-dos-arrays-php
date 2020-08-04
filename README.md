# Diferencias entre dos arrays php

```php
$array1    = array("a" => "green", "red", "blue", "red");
$array2    = array("b" => "green", "yellow", "red");
$resultado = array_diff($array1, $array2);

print_r($resultado);
```

Resultado
```Array
(
    [1] => blue
)
```

Use ```array_values``` para resetear los keys

Fuente: https://www.php.net/manual/es/function.array-diff.php
