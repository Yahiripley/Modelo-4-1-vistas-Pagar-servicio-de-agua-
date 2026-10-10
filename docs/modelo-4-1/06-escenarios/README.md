# 06. Escenarios (+1)

Los escenarios conectan las cinco vistas y sirven para comprobar que todas
describen el mismo comportamiento.

## Escenario principal

Un cliente ingresa su número de servicio, consulta su consumo y adeudo,
selecciona un saldo, proporciona un método de pago y confirma la operación.
El sistema valida los datos, solicita autorización, registra el pago aprobado
y genera un comprobante.

## Escenarios por documentar

- Cliente no encontrado.
- Sistema comercial no disponible.
- Datos de pago inválidos.
- Pago rechazado.
- Transacción pendiente y reintento.
- Doble intento de pago.
- Cancelación antes de confirmar.
- Notificación no disponible después de registrar el pago.

Cada escenario debe indicar qué casos de uso, componentes, procesos y nodos
participan.
