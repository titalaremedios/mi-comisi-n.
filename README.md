# Mi Comisión

Aplicación web móvil para controlar ventas, tramos de comisión y sorteos extraordinarios.

## Funciones principales
- Registro diario: Pasivo, Activo, Rascas, Pagos y Tarjeta.
- Venta diaria automática = Pasivo + Activo + Rascas.
- A liquidar = Venta - Pagos - Tarjeta.
- Total acumulado mensual.
- Tramos ordinarios: 2,5 %, 6 %, 10 %, 13 %, 14 %, 15 %, 16 % y 17,5 %.
- Camino visual de tramos con fechas en las que se alcanza cada uno.
- Proyección del tramo probable al cierre del mes.
- Histórico y comparativa mensual de ventas y tramo alcanzado.
- Resumen final de cada mes completado.
- Registro de sorteos EXTRA con número de cupones, precio, porcentaje y comisión estimada.
- Escala automática para extraordinarios: hasta 199 = 12 %, 200–299 = 13 %, 300–399 = 14 %, 400–499 = 15 %, 500–599 = 16,5 %, 600+ = 17,5 %.
- Posibilidad de indicar porcentaje manual para un extra que use otra escala.
- Saludo personalizado y frase de ánimo diaria.
- Copias de seguridad mediante exportación/importación JSON.

Los datos se guardan en el navegador del dispositivo mediante localStorage.

## Seguimiento administrativo
- Ingresos a cuenta por mes, con fecha, importe, referencia y asociación opcional a un extra.
- Total ingresado a cuenta, número de ingresos y último ingreso del mes.
- Incidencias mensuales: médico, ausencia, permiso, avería, cambio de jornada u otras.
- Posibilidad de marcar una incidencia como día de ausencia sin modificar automáticamente los objetivos.
- Comparativa histórica con ingresos a cuenta e incidencias.

## Catálogo de rascas y grupos de comisión
La app incluye el catálogo mostrado en las tablas de julio de 2026, con precio, porcentaje de premios y grupo: Resto de productos, Alto % de premios o Muy alto % de premios. También conserva el valor automático por paquete: 100 € para 0,50/1/2 € y 150 € para 3/5/10 €.
