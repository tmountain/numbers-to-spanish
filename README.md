# numbers-to-spanish

Converts numbers to text in Spanish.

**Spanish:** Esta clase convierte cualquier número a su respectivo texto en español. (Los decimales son ignorados. El número debe estar entre el rango de -1 billón a +1 billón). 

Basado en el trabajo de AxiaCore S.A.S.  
[https://github.com/AxiaCore/numero-a-letras/tree/master/php](https://github.com/AxiaCore/numero-a-letras/tree/master/php)

**Ejemplo de Uso**
```php
$number = -123;
$numbersToSpanish = new NumbersToSpanish();
$field = $numbersToSpanish->getText($number);

echo $field['number'].' '.$field['text'];
// Output: -123 MENOS CIENTO VENTITRES
```    
