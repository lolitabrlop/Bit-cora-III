# Bit-cora-III
Fundamentos de seguridad y autoría
## Fase de investigación
1- Los Syslog se usan para que los dispositivos puedan generar sus propios registros. Se encuentran los severity (0-7) y los facility, que son claves que facilitan las búsquedas.
Hay que tener cuidado con poner los permisos de lecturas a usuarios no privilegiados ya que se expondría la autentificación y la seguridad del sistema. 

2- Las ventajas de custodiar los losg en un servidor externo:
  -Garantizan la inmutabilidad de la información, permitiendo investigar el incidente
  -Unifica los registros de múltiples servidores, aplicaciones y dispositivos de red en una única ubicación.
  -Mejorar el rendimiento del servidor.
  -Un servidor puede gestionar grandes volúmenes de datos mediante rotaciones de logs.
  -Facilita la implementación de herramientas  de análisis que analizan los logs en tiempo real para alertar de los errores.

## Fase Práctica
-Reto A
A través de PowerShell de windows he añadido un usuario inventado con la ip de mi máquiona virtual pero, cuando he ido a comprobar los intentos del supuesto ataque, no sale reflejado. 
En la parte de hacer el scripts es por donde me he quedado, pero, no creo que me genere el informe de los fallos si previamente no lee los intentos de ataque.
