# magento1-redsys-referencia
Redsys module for Magento 1 which implements «Pago por referencia»


# Redsys Test Cards

| Resultado  | PAN | 3DSecure v.2 | 3DSMethod | Tipo de autorización |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Autorización | 4548812049400004 | Falso | Falso | CIP |
| Autorización | 5101332200023012 | Falso | Falso | Falso |
| Autorización | 374245455400001 | Falso | Falso | Falso |
| Autorización | 4918019160034602 | Verdadero | Verdadero | Frictionless |
| Autorización | 4548814479727229 | Verdadero | Falso | Frictionless |
| Autorización | 4918019199883839 | Verdadero | Verdadero | Challenge |
| Autorización | 4548817212493017 | Verdadero | Falso | Challenge |
| Denegación 190 | 5576440022788500 | Falso | Falso | CIP |
| Denegación 190 | 4907277775205123 | Verdadero | Verdadero | Frictionless |
| Denegación 190 | 4907271141151707 | Verdadero | Verdadero | Challenge |
| Denegación 9598 | 5410082854557833 | Verdadero | Falso | 
| Denegación 9598 | 5410088208000685 | Verdadero | Falso | 
 
Validación pago/tarjeta: 

* Caducidad: Cualquiera válida
* CVV2: 3 dígitos para Visa y Mastecard, 4 dígitos para AMEX
* CIP: 123456
