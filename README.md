Una empresa de transporte ha desarrollado un sistema para procesar pagos de sus clientes. Inicialmente, solo aceptaban pagos con tarjeta de crédito, pero ahora desean agregar soporte para PayPal y criptomonedas.
Actualmente, la clase ProcesadorPagos está acoplada a la clase PagoTarjeta, lo que hace difícil agregar nuevas formas de pago sin modificar su código.

Implementar tres clases concretas:
PagoTarjeta (procesa pagos con tarjeta de crédito).
PagoPayPal (procesa pagos con PayPal).
PagoCripto (procesa pagos con criptomonedas).
Modificar la clase ProcesadorPagos para que dependa de una abstracción en lugar de una implementación concreta.
Permitir que el método de pago se pueda cambiar en tiempo de ejecución al instanciar ProcesadorPagos.
Crear un programa principal (Main) donde se demuestre el uso del sistema con diferentes métodos de pago.
