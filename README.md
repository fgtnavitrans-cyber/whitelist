⚠️ Advertencia – Uso de Lista de Whitelist de IP

Este archivo contiene un listado de direcciones IP que serán integradas directamente como parte de una política de Whitelist (sin inspección/filtrado completo).

IMPORTANTE:

Toda IP incluida en este listado tendrá acceso sin restricciones de seguridad (sin UTM, sin inspección profunda).
La inclusión de una IP implica un riesgo potencial de seguridad, ya que el tráfico proveniente de dicha fuente no será analizado ni filtrado.
Este archivo es considerado crítico dentro de la postura de seguridad de la organización.

Responsabilidad de los colaboradores:

Solo agregar IPs estrictamente necesarias y justificadas.
Validar que las IPs correspondan a fuentes confiables y controladas.
Evitar rangos amplios (ej. /8, /16) salvo aprobación explícita.
Documentar cada cambio indicando:
Motivo
Responsable
Fecha
Revisar periódicamente las IPs añadidas y eliminar las que ya no sean necesarias.

Nota:
Cualquier uso indebido o inclusión incorrecta puede generar brechas de seguridad, accesos no autorizados o exposición de servicios críticos.
