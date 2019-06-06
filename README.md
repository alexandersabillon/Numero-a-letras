# Numero-a-letras
Basado en la clase de arielcr/numero-a-letras 

Convierte un número a su valor correspondiente en letras.

Uso:
$letras = NumeroALetras::convertir(12345);
$letras = NumeroALetras::convertir(12345.67, 'lempiras', 'centavos');

Corregido la parte de los centavos al no convertir valores de un solo dígito. Ejemplo: 50.30, la clase solamente me devuelve CINCUENTA y no CINCUENTA CON TREINTA


