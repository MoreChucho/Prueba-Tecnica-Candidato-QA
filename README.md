SECCIÓN II: Pruebas de Automatización Estrategia de Automatización Móvil:

¿Qué herramienta principal (ej. Appium, Selenium, Calabash, etc.) y qué lenguaje de programación elegiría para automatizar el flujo de transferencia y por qué?
La herramienta que utilizaría es Appium. Appium es la mejor opción porque es de código abierto, soporta aplicaciones nativas, híbridas y web móviles, funciona tanto para iOS como Android con la misma API, es compatible con Flutter a través del driver específico para Flutter, permite escribir pruebas una vez y ejecutarlas en ambas plataformas.

Describa brevemente la estrategia a seguir para maximizar la reutilización de código en ambos sistemas operativos (iOS/Android) con su elección de herramienta.
Estrategia Modelo de objetos de página (POM) con abstracción de plataforma. Para la arquitectura de objetos de página se podrá crear clases abstractas para elementos comunes de transferencia. Implementar variaciones específicas solo cuando los elementos UI difieran entre plataformas.
