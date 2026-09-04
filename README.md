# Project Security

Sistema inteligente de videovigilancia con reconocimiento facial, análisis inteligente de eventos y control de accesos.

## Problema

Los sistemas tradicionales de videovigilancia dependen principalmente de la supervisión humana, la cual puede verse afectada por la fatiga, la saturación de información y los errores de omisión.

Además, muchos sistemas actuales se limitan a registrar lo ocurrido sin interpretar de manera automática comportamientos sospechosos, intentos de acceso no autorizado o situaciones potencialmente riesgosas.

Esto provoca que la videovigilancia funcione principalmente como una herramienta de consulta posterior a un incidente, en lugar de actuar como un sistema capaz de detectar oportunamente posibles amenazas.

## Objetivo general

Desarrollar un sistema inteligente de videovigilancia mediante técnicas de visión computacional que permita analizar video, reconocer personas, detectar eventos potencialmente riesgosos y generar alertas que apoyen la supervisión y el control de accesos.

## Objetivos particulares

1. Implementar un módulo de procesamiento de video capaz de detectar personas dentro de un área monitoreada.
2. Desarrollar un módulo de reconocimiento facial para identificar usuarios registrados y personas desconocidas.
3. Implementar un mecanismo de registro y clasificación de eventos detectados por el sistema.
4. Desarrollar un sistema de alertas que notifique al administrador cuando se detecte un evento relevante o potencialmente riesgoso.

## Alcance

El proyecto contempla:

- Procesamiento de video proveniente de cámaras o archivos de prueba.
- Detección de personas mediante visión computacional.
- Reconocimiento facial de usuarios previamente registrados.
- Identificación de personas desconocidas.
- Registro de usuarios autorizados.
- Registro de accesos y eventos detectados.
- Detección inicial de patrones o conductas relevantes.
- Generación de alertas.
- Almacenamiento de información en una base de datos.
- Interfaz básica para consulta y administración.
- Pruebas de precisión del sistema.

## Fuera de alcance

Para la primera versión del proyecto no se contempla:

- Sustituir completamente al personal de seguridad.
- Operar sin supervisión humana.
- Implementar el sistema a gran escala en múltiples instalaciones.
- Integrarse con sistemas policiales o gubernamentales.
- Automatizar acciones físicas como bloqueo de puertas sin validación adicional.
- Desarrollar aplicaciones móviles.
- Realizar un despliegue comercial.

## MVP

El Minimum Viable Product consistirá en una aplicación capaz de recibir un flujo de video o un archivo grabado y procesarlo mediante visión computacional.

El sistema deberá ser capaz de:

- Detectar personas.
- Detectar rostros.
- Comparar rostros con usuarios registrados.
- Identificar personas conocidas o desconocidas.
- Registrar los eventos detectados.
- Almacenar información básica de los eventos.
- Mostrar los eventos en una interfaz básica.
- Generar una alerta cuando se detecte una persona desconocida o un evento relevante.
