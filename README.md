# CRM Flowdex — incidencias y mejoras

Repositorio público de seguimiento documental del CRM Flowdex de Vivibox, desarrollado por un proveedor independiente. Proyecto registrado en Hidra como **CRM Flowdex — incidencias y mejoras**, identificador `crm_flowdex_pancake`.

**Corte de los datos: 21 de octubre de 2026.** Es una copia pública depurada del mapa de incidencias y mejoras. Contiene documentación y datos de seguimiento; no contiene el código fuente del CRM.

## Consultar el proyecto

- [Mapa de 68 casos](docs/MAPA.md)
- [Cronología de 57 hitos](docs/CRONOLOGIA.md)
- [Mapa CSV para Excel](datos/mapa_publico.csv) · [JSON](datos/mapa_publico.json)
- [Cronología CSV para Excel](datos/cronologia_publica.csv) · [JSON](datos/cronologia_publica.json)
- [Metodología, discrepancias y pendientes](docs/METODOLOGIA.md)
- [Alcance de esta copia pública](docs/PUBLICACION.md)
- [Comprobaciones de publicación](validacion.json)

## Situación al corte

| Indicador | Resultado |
| --- | ---: |
| Registros estables | 68 |
| Requieren atención | 39 |
| Cerrados según fuente | 29 |
| Bloqueantes entre los que requieren atención | 5 |
| Mensajes revisados en dos grupos | 356 |
| Hitos documentales | 57 |
| Casos vinculados a los grupos | 22 |
| Asuntos por vincular | 7 |

Los cinco bloqueantes en atención son **FD-049, FD-054, FD-058, FD-060 y FD-068**. FD-031 y FD-060 presentan discrepancias de cierre entre versiones. FD-026 requiere revisar una posible reapertura posterior a su cierre documental.

Un cierre en el cuadro o una corrección anunciada no equivalen a una prueba funcional. Los reenvíos, seguimientos y persistencias se distinguen de una reincidencia posterior a un cierre validado. Los datos disponibles no permiten certificar reincidencias con ese último criterio.

## Uso en Excel

Descargar el CSV y usar **Datos → Desde texto/CSV**, seleccionando UTF-8 y separador coma. Las fechas están en formato ISO. `jornadas_con_reporte` cuenta fechas distintas con reporte directo, no reincidencias ni duración continua de una falla.

## Actualizaciones

Mantener los identificadores FD y EV. Separar evidencia, estado documental, hipótesis y validación real. Registrar fecha de corte en cada actualización. Antes de cargar archivos, revisar el alcance público descrito en [PUBLICACION.md](docs/PUBLICACION.md).

La memoria completa en Hidra y los originales locales se mantienen como respaldo interno. No hay sincronización automática con Drive ni con Hidra.
