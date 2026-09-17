# Cuenta Clara

Tu jornada. Tus cuentas. Todo claro.

Aplicación web móvil para vendedores de la ONCE orientada al control personal de:
- jornadas
- cupones
- activos
- rascas
- extras
- liquidaciones
- comisiones estimadas
- calendario e historial
- copias de seguridad

Los datos se guardan localmente en el navegador del dispositivo.

## Versión
v0.41.0


### Nuevo en v0.22
- Comparativa de ventas por día de la semana.
- Promedio, último resultado, variación y tendencia.
- Solo cuenta jornadas realmente trabajadas con ventas.


### Nuevo en v0.22
- Ayudas contextuales con botón ? en conceptos clave.
- Guía completa 'Cómo usar Cuenta Clara' dentro de Ajustes.
- Manual PDF para entregar a otros vendedores.


### Nuevo en v0.22
- Diferencia claramente la comisión estimada de la jornada anterior y la comisión estimada acumulada del mes.
- La comisión mensual aparece en la tarjeta principal de Inicio.
- La comisión de extras, si existe, aparece aparte.


### Nuevo en v0.22
- Tarjeta de comisión mensual más compacta.
- Texto simplificado a “Comisión estimada del mes”.
- Ayuda y cantidad alineadas en la misma fila.


## v0.28
- Nueva identidad visual definitiva: Cuenta Clara.
- Paleta verde petróleo/menta.
- Icono de app renovado.
- Iconos visuales y variaciones suaves de color en tarjetas principales.


## v0.33
- Acabado final de la pantalla principal.
- Iconos integrados sin aumentar la altura de las tarjetas.
- Ayuda (?) alineada arriba a la derecha en comisión, tramo y proyección.
- Comisión mensual simplificada: el desglose interno no ocupa espacio en Inicio.
- Espaciados compactados manteniendo legibilidad.


## v0.37
- Aviso automático al abrir cuando hay una versión nueva publicada.
- Botones Actualizar ahora / Más tarde.
- Se mantiene la actualización manual en Ajustes.


## v0.38
- Introducción automática la primera vez que se abre Cuenta Clara.
- Explica instalación, configuración inicial y uso diario.
- Botón para repetir la introducción desde Ajustes.


## v0.41.0 — revisión integral
- Auditoría completa de coherencia visual, textos, móvil y cálculos.
- La comparativa por día de la semana ya no necesita desplazamiento horizontal.
- Tramo y comisión ordinaria usan el mismo objetivo mensual previsto.
- Nueva jornada abre por defecto la jornada anterior.
- Se impiden jornadas duplicadas del mismo día.
- Validaciones reforzadas en cupones, extras, tarjeta e ingresos a cuenta.
- Campos numéricos manuales vuelven a quedar vacíos, nunca con un 0 forzado.
- Identidad verde unificada y limpieza de restos azules/morados.
- Versión interna actualizada para que los avisos automáticos de nuevas versiones funcionen.
- Copias de seguridad exportadas como cuenta-clara-copia.json.


## v0.44.0 — Otros productos
- Nuevo bloque “Otros” dentro de Añadir jornada.
- Productos: Paysafecard, Amazon, Google, Topii y Otro.
- Permite añadir varios productos e importes en una misma jornada.
- “Otros” se suma exclusivamente a la liquidación.
- No se añade a Venta ONCE, tramos ni comisión.
- Los importes quedan visibles en el detalle de la jornada y en la liquidación.


## v0.45.0 — Piloto de foto para Activos
- Nuevo botón “📷 Leer cierre de ventas” en Añadir jornada.
- Esta primera prueba no necesita API, clave ni servidor.
- Usa OCR en el propio navegador; requiere conexión a internet para cargar el lector.
- Reconoce inicialmente EUJ, TRI, MID, DUP y SUP.
- ORD se marca como pendiente de identificar y nunca se añade automáticamente.
- Siempre muestra una revisión antes de añadir los datos a Activos.
- Si la fiabilidad no es suficiente, el siguiente paso será probar una API de visión desde servidor.


## v0.46.0 — Tarjetas de jornada en una sola columna
- En móvil, cada tarjeta de “Tu jornada anterior” ocupa una fila completa.
- Vendido, comisión estimada, comisión por extras y pendiente de liquidar ya no comparten fila.
- Se mejora la legibilidad y se evita que títulos o textos queden apretados.


## v0.48.0 — Rascas con liquidación aplazada
- Opción visible dentro de Rascas por paquetes.
- Fecha de liquidación futura.
- Cuenta en venta/tramo/comisión desde hoy, pero no en pendiente de liquidar hasta confirmación.
- Tarjeta de Rascas aplazados en Inicio.


## v0.49.0 — Actualización del catálogo de rascas
- “7 de la Suerte 2025” se sustituye por “7 de la Suerte 2026” para nuevas jornadas.
- “Millonario 2024” se sustituye por “Millonario 2026” para nuevas jornadas.
- “Rasca de Verano 2026” se retira del catálogo vigente.
- Los registros históricos de los modelos antiguos se conservan sin cambios.


## v0.50.0 — Primer paquete del nuevo modelo no computable
- Nueva opción dentro de Rascas: “Primer paquete del nuevo modelo · no computable”.
- Se registra para el control de paquetes.
- No suma a venta ONCE, liquidación, tramo ni comisión.
- Queda identificado en la jornada con una etiqueta.
- No puede combinarse con “liquidación aplazada”.


## v0.51.0 — Puntos colaboradores
- Nuevo control para bares, cafeterías, peluquerías, tiendas y otros establecimientos que ayudan a vender cupones.
- Se pueden guardar varios puntos y seleccionarlos desde Nueva jornada.
- Por entrega: cupón, fecha de sorteo, llevados y devueltos.
- Vendidos = llevados − devueltos.
- Este control no vuelve a sumar venta ni liquidación, evitando duplicados.
- Resumen mensual e histórico por establecimiento.
- Gestión de puntos colaboradores desde Ajustes.
