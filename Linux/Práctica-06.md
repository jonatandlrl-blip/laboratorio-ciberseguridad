# Práctica 06: Seguridad básica en Linux

## Objetivo
Conocer medidas básicas para mejorar la seguridad de un sistema Linux.

## Conceptos básicos
- Actualizaciones: corrigen errores y vulnerabilidades.
- Mínimo privilegio: utilizar únicamente los permisos necesarios.
- Firewall: controla el tráfico de red permitido y bloqueado.
- Registros (logs): almacenan información sobre la actividad del sistema.

## Comandos estudiados
- `sudo`: ejecuta comandos con privilegios autorizados.
- `sudo apt update`: actualiza la información de los paquetes disponibles.
- `sudo apt upgrade`: actualiza los paquetes instalados.
- `ufw status`: consulta el estado del firewall UFW.
- `journalctl`: permite consultar los registros del sistema.


## Procedimiento

1. Consultar las actualizaciones disponibles del sistema.
2. Revisar el estado del cortafuegos UFW.
3. Consultar los registros del sistema.
4. Aplicar las actualizaciones únicamente cuando proceda y con autorización.

## Resultados

Se documentarán los resultados reales obtenidos al ejecutar los comandos de consulta y mantenimiento.

- `sudo apt update`: actualiza la información de los paquetes disponibles.
- `sudo apt upgrade`: instala las actualizaciones disponibles de los paquetes instalados, previa confirmación cuando corresponda.
- `sudo ufw status`: muestra el estado del cortafuegos UFW.
- `journalctl`: permite consultar los registros del sistema.

## Conclusión

La práctica permite conocer medidas básicas de seguridad en Linux, como mantener el sistema actualizado, comprobar el estado del cortafuegos y consultar los registros para revisar la actividad del sistema.

Las comprobaciones y los resultados deberán quedar documentados con evidencias reales.


## Observaciones
Documentar las comprobaciones realizadas y sus resultados. Aplicar cambios de seguridad únicamente en sistemas propios o autorizados.
