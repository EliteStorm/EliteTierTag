# Changelog

Todos los cambios notables en este proyecto se documentan en este archivo.

El formato se basa en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/),
y este proyecto se adhiere a [Semantic Versioning](https://semver.org/lang/es/).

## [b1.1.1] - 2026-07-08

### Fixed
- **Skins en la comparación**: el jugador de la derecha ya aparece con su skin correctamente.
- **Panel borroso**: la interfaz se ve clara, sin desenfoque de fondo.
- **Texto solapado en pantallas pequeñas**: se ajusta automáticamente sin choques ni deformaciones.
- **Cargar datos de tiers y skins**: funciona de forma más confiable, ahora sigue redirecciones web.
- **Botón de refresco (↺)**: tiene límite de 10 segundos para no saturar peticiones, solo actualiza el jugador que ves.
- **Modos Mace y Vanilla**: ahora funcionan correctamente en PvPTiers.
- **Enlace de perfil**: ahora abre NameMC (el estándar de la comunidad).

### Improved
- **Cache de perfiles**: los perfiles se reutilizan durante 60 segundos en lugar de pedir dos veces.
- **Optimización de peticiones**: mejora general del rendimiento al consultar la API de EliteStorm.

## [b1.1.0] - 2026-07-05

### Added
- Traducción completa a español, catalán e inglés en todas las versiones.
- Panel de perfil y herramienta de comparación entre jugadores.
- Atajos de teclado (hotkeys) para abrir panel, cambiar lista tierlist y modo.
- Compatibilidad con MCTiers y PvPTiers.

### Improved
- Optimización general de peticiones a la API de EliteStorm.