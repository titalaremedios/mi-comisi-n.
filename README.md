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


## v0.52.0 — Nuevo rasca Halloween
- Se añade Halloween al catálogo vigente.
- Precio: 3 €.
- Porcentaje de premios: 65,50 %.
- Categoría interna: Alto.
- La categoría se determina por el porcentaje de premios, no por el precio del rasca.


## v0.53.0 — Corrección de escritorio
- Nueva jornada se abre más ancha en ordenador.
- Se corrige el contenido cortado y el desbordamiento lateral.
- Los bloques se reorganizan para aprovechar el ancho de pantalla.
- El diseño móvil se mantiene sin cambios.
- No se modifica ninguna lógica ni cálculo.


## v0.54.0 — Ajuste de venta acumulada y proyección
- La cifra de “Venta acumulada” se adapta mejor al ancho del móvil y el símbolo € ya no debe salirse de la tarjeta.
- Se corrige el mensaje de proyección del tramo.
- Si la proyección todavía no alcanza matemáticamente el siguiente tramo, la app indica cuánto faltaría exactamente.
- Ejemplo: si proyecta 10.982,49 € y el 15 % empieza en 10.983,00 €, mostrará que faltan solo 0,51 € para el 15 %, en vez de limitarse a decir que llegará al 14 %.
- No se modifican los umbrales ni los cálculos de comisión: solo se mejora la lectura y la explicación de la proyección.


## v0.55.0 — Cambiar / crear mes
- Nuevo botón visible en Inicio: “Cambiar / crear mes”.
- Permite pasar fácilmente de septiembre a octubre o volver a cualquier mes ya creado.
- Si eliges un mes existente, conserva todos sus datos y recupera sus jornadas previstas.
- Si eliges un mes nuevo, se crea sin borrar el histórico anterior.
- El formulario explica claramente si estás abriendo un mes existente o creando uno nuevo.


## v0.56.0 — Días festivos
- Nuevo tipo “Festivo”, separado de Médico/Ausencia.
- Nuevo botón “Añadir festivo” en Incidencias y festivos.
- Al guardar un festivo, ese día se marca automáticamente como no laborable.
- En el calendario los festivos aparecen en rojo/rosa con icono 🎉 y texto “Festivo”.
- También puede añadirse “Día festivo” desde Ajustes > Excepciones del calendario.
- Un festivo ya no aparece como si hubieras ido al médico.


## v0.57.0 — Cierre de liquidaciones negativas o a cero
- Cuando toca liquidar y el pendiente es 0 € o negativo, aparece “✅ Entendido · cerrar liquidación”.
- Al cerrar, la jornada queda marcada como liquidada aunque no haya importe positivo que pagar.
- El saldo negativo no desaparece: queda registrado como saldo a favor para compensar en la siguiente liquidación.
- En el calendario, una liquidación cerrada con saldo negativo se muestra como liquidada en verde con un indicador rojo 🔴.
- Amarillo queda reservado para movimientos realmente pendientes de cerrar.


## v0.58.0 — Saldo a favor anterior
- Nuevo campo en Ajustes para introducir un saldo a favor que ya existía antes de empezar a usar Cuenta Clara.
- El saldo se muestra claramente en Inicio.
- Se descuenta automáticamente de las siguientes liquidaciones.
- Si una liquidación queda totalmente cubierta por ese saldo, puede cerrarse y el resto continúa guardado.
- Si una jornada genera un nuevo saldo negativo, se suma al saldo a favor existente.
- El histórico de liquidaciones indica cuánto saldo se aplicó y cuánto queda pendiente de compensar.


## v0.59.0 — Saldo pendiente permanente
- El saldo ya no es solo “inicial” ni solo a favor.
- En Ajustes puedes introducir un saldo anterior “A mi favor” o “Pendiente de pagar” al empezar a usar la app.
- Si el saldo se genera dentro de Cuenta Clara, se arrastra automáticamente aunque cambies de mes o estés de vacaciones.
- Saldo a favor: se descuenta de las siguientes liquidaciones.
- Saldo pendiente de pagar: se añade a la siguiente liquidación.
- Cuando el saldo queda compensado, vuelve automáticamente a 0 €.
- La tarjeta de Inicio cambia de color y texto según sea saldo a favor o saldo pendiente de pagar.


## v0.61.0 — Saldo pendiente permanente sobre la v60
- Mantiene el acceso por código y el panel de administración de la v60.
- Nuevo “Saldo pendiente anterior” en Ajustes.
- Permite saldo 💚 a favor o 🔴 pendiente de pagar.
- Si el saldo nace dentro de Cuenta Clara, se arrastra automáticamente entre meses y vacaciones.
- El saldo a favor se descuenta de siguientes liquidaciones.
- El saldo pendiente de pagar se suma a la siguiente liquidación.


## v0.62.0 — 2 dispositivos + ORD/VIE por fecha
- El panel de administración permite cambiar una licencia ya creada de 1 a 2 dispositivos (y viceversa) sin liberar el dispositivo existente.
- El mismo código puede activarse en el segundo dispositivo cuando la licencia tenga límite 2.
- El lector de cierre reconoce ORD como Cupón Ordinario (lunes-jueves) y VIE como Cupón Viernes.
- Los cupones TPV leídos se guardan por la fecha que aparece en el ticket.
- Cuando se abre la jornada de esa fecha, el TPV aparece ya precargado en Control de cupones.
- Se evita volver a guardar exactamente la misma línea OCR si ya estaba pendiente o guardada.
- Los activos EUJ/TRI/MID/DUP/SUP continúan funcionando como antes.


## v0.63.0 — Pasivos futuros dentro de la jornada real de venta
- La fecha de jornada y la fecha de sorteo son independientes.
- Si el viernes se venden cupones del viernes, sábado, domingo o lunes, todos pueden quedar dentro de la jornada del viernes.
- ORD y VIE leídos por foto se añaden directamente a la jornada abierta, conservando su fecha de sorteo.
- Si después se añade manualmente el mismo cupón (misma fecha + mismo tipo), se junta con el TPV ya detectado en vez de duplicarse.
- BON/BONO se reconoce como Bono semanal, a 15 € por unidad, y conserva la fecha que aparece en el ticket.
- El bono detectado por OCR también se suma al Pasivo de la jornada en la que realmente se vendió, aunque su sorteo sea posterior.
- Los activos EUJ/TRI/MID/DUP/SUP continúan funcionando igual.


## v0.64.0 — Bono manual en cualquier jornada
- El bono semanal ya se puede añadir manualmente en cualquier jornada.
- Esto permite registrarlo, por ejemplo, en la jornada del viernes aunque el sorteo corresponda al lunes.
- Sigue contando 15 € por unidad y se suma automáticamente al Pasivo de esa jornada.
- La lectura por foto sigue funcionando igual.


## v0.65.0 — TPV leído por foto, aplicado al seleccionar la fecha
- La foto puede leer cupones de varias fechas, pero ya NO los suma todos de golpe a la jornada.
- ORD/VIE quedan temporalmente memorizados por fecha de sorteo.
- Al seleccionar una “Fecha sorteo” en Control de cupones, la casilla “TPV vendidos” se rellena automáticamente si la foto había detectado ventas para esa fecha.
- Esto funciona aunque todos esos sorteos (viernes, sábado, domingo, lunes festivo) se guarden dentro de una única jornada del viernes.
- El Bono semanal tiene ahora “Fecha del bono”.
- Si la foto detectó un bono para esa fecha, “Bonos vendidos” se rellena automáticamente.
- El bono puede introducirse manualmente en cualquier jornada y sigue valiendo 15 € por unidad.


## v0.66.0 — TPV solo al elegir la fecha
- Hacer la foto NO añade ningún cupón TPV al Pasivo ni a la venta.
- ORD/VIE/BONO quedan memorizados por fecha.
- Solo al seleccionar “Fecha sorteo” aparece el TPV detectado para esa fecha.
- Al aparecer en “TPV vendidos” todavía no se suma: entra en la venta únicamente al pulsar “Añadir sorteo”.
- Se limpian los campos de cupón al abrir la jornada para impedir que una fecha antigua active TPV por accidente.
