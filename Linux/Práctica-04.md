# Práctica 04: Procesos y servicios en Linux

## Objetivo
Aprender a identificar y gestionar los procesos que se ejecutan en Linux.

## Conceptos básicos
- Proceso: programa que está en ejecución.
- PID: número que identifica a cada proceso.
- Servicio: programa que funciona en segundo plano.

## Comandos estudiados
- `ps`: muestra los procesos activos.
- `top`: permite observar los procesos en tiempo real.
- `pgrep`: busca procesos por su nombre.
- `kill`: envía una señal a un proceso.
- `systemctl`: permite consultar y gestionar servicios del sistema.

## Observaciones
Registrar los comandos utilizados y los resultados obtenidos. Ejecutar acciones de gestión únicamente sobre procesos propios o en un entorno autorizado.

## Comandos estudiados

- `pgrep`: busca procesos por su nombre.
- `kill`: envía una señal a un proceso identificado por su PID.
- `ps`: consultar los procesos activos en la sesión.
- `ps aux`: consultar los procesos del sistema.
- `top`: observar la actividad de los procesos en tiempo real.
- `pgrep bash`: buscar procesos cuyo nombre coincida con bash.
- `systemctl status cron`: consultar el estado del servicio cron, si está disponible en el sistema.

## Resultados

Los comandos estudiados permiten identificar procesos, consultar su estado y observar la actividad del sistema Linux.

- `pgrep`: permite localizar procesos por su nombre.
- `ps`: muestra información sobre los procesos en ejecución.
- `ps aux`: ofrece información detallada de los procesos activos.
- `top`: permite observar los procesos y el consumo de recursos en tiempo real.
- `pgrep bash`: permite buscar procesos cuyo nombre coincide con `bash`.
- `kill`: permite enviar una señal a un proceso identificado mediante su PID.
- `systemctl status cron`: permite consultar el estado del servicio cron.

Estas herramientas facilitan la supervisión de procesos y servicios. Los resultados concretos dependerán de los procesos y servicios presentes en el sistema durante la práctica.

## Conclusión

Esta práctica permite conocer cómo identificar procesos, consultar su actividad y comprobar el estado de los servicios en Linux.
