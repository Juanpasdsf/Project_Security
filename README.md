# Project Security
 
Sistema inteligente de videovigilancia y acceso facial para CUCEI, con detección de vida (anti-spoofing), análisis de eventos de riesgo y alertas centralizadas.
 
## Contexto y problema
 
El Centro Universitario de Ciencias Exactas e Ingenierías (CUCEI) recibe a diario a una gran cantidad de estudiantes, docentes y personal administrativo y de servicio. Por su tamaño y flujo de personas, controlar quién ingresa y qué ocurre dentro de sus instalaciones es clave para un ambiente seguro.
 
Actualmente la seguridad en los accesos es ineficiente y la vigilancia interna es escasa o casi nula, lo que expone a la comunidad a que personas no autorizadas ingresen y permanezcan en las instalaciones sin ser detectadas.
 
Los rehiletes con identificación facial actuales cumplen su función básica, pero:
 
- Son vulnerables al *spoofing* (fotografías, videos u otros medios que suplantan una identidad) por no contar con detección de vida.
- La sensibilidad de sus sensores provoca que, en ocasiones, se niegue el acceso a personas autorizadas.
- La vigilancia no se extiende más allá de los puntos de entrada, y la videovigilancia funciona sobre todo como consulta posterior a un incidente, dependiendo de la supervisión humana (sujeta a fatiga y errores de omisión).
## Objetivo general
 
Desarrollar un sistema inteligente de videovigilancia y acceso facial en CUCEI para garantizar ingresos seguros y optimizar la respuesta operativa de seguridad.
 
**Meta medible:** procesar flujos de video en tiempo real y registrar eventos detectados con una latencia inferior a 3 segundos en al menos el 90% de las pruebas controladas del semestre 2026B.
 
## Objetivos particulares
 
1. **Detección de vida:** implementar detección de vida en los rehiletes de acceso para evitar ingresos por suplantación de identidad (spoofing).
2. **Detección de amenazas:** desarrollar un módulo de visión artificial que detecte armas o atuendos sospechosos (p. ej. pasamontañas) para alertar y bloquear amenazas.
3. **Plataforma de alertas:** integrar una plataforma centralizada de alertas y accesos, y capacitar al personal de seguridad para asegurar una respuesta rápida y efectiva.
## Alcance
 
El proyecto contempla:
 
- Procesamiento de video proveniente de cámaras o archivos de prueba.
- Detección de personas y rostros mediante visión computacional.
- Reconocimiento facial de usuarios registrados e identificación de personas desconocidas.
- Detección de vida (anti-spoofing) en el punto de acceso.
- Detección inicial de armas y atuendos sospechosos.
- Registro de usuarios autorizados, accesos y eventos detectados.
- Generación de alertas para el personal de seguridad.
- Almacenamiento en base de datos.
- Interfaz básica (plataforma centralizada) para consulta y administración.
- Pruebas de precisión, de resistencia a spoofing y de tiempos de respuesta.
- Plan de capacitación para el personal de seguridad.
## Fuera de alcance (primera versión)
 
- Sustituir completamente al personal de seguridad u operar sin supervisión humana.
- Integración con sistemas policiales o gubernamentales.
- Bloqueo físico automático de accesos sin validación adicional del personal de seguridad.
- Despliegue simultáneo en todos los accesos de CUCEI (la primera versión se valida en un acceso o entorno de pruebas).
- Aplicaciones móviles y despliegue comercial.
## MVP
 
Aplicación capaz de recibir un flujo de video o un archivo grabado y procesarlo con visión computacional. Deberá:
 
- Detectar personas y rostros.
- Comparar rostros con usuarios registrados e identificar personas conocidas o desconocidas.
- Verificar detección de vida básica para rechazar intentos con fotografías o video.
- Registrar y almacenar los eventos detectados.
- Mostrar los eventos en una interfaz básica.
- Generar una alerta cuando se detecte una persona desconocida, un intento de spoofing o un evento relevante.
## Siguiente paso
 
Configurar el módulo de captura de video con OpenCV y realizar las pruebas iniciales de conexión y lectura de frames con una cámara IP/local de prueba.
 
### Pruebas iniciales de captura de video
 
Antes de integrar la captura al sistema:
 
- **Conexión:** verificar que la cámara local o IP de prueba se abra correctamente.
- **Lectura de frames:** comprobar que se reciben imágenes de manera continua.
- **Manejo de errores:** registrar los problemas de conexión o lectura que se presenten.
**Resultados esperados:** la cámara se abre, se reciben frames y los errores pueden identificarse y documentarse.
 
**Estado:** pruebas pendientes de ejecución.
