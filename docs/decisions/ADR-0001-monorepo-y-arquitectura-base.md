# ADR-0001: Monorepo y arquitectura base

- **Estado:** propuesta inicial para validar durante el MVP.
- **Fecha:** 6 de noviembre de 2026.

## Contexto

NEXUS CAMPUS requiere una aplicación móvil, un panel administrativo, un backend, documentación y pruebas. Al inicio, mantenerlos en un solo repositorio facilita su coordinación y versionado.

## Decisión propuesta

Organizar el código en un monorepo con `apps/mobile`, `apps/web-admin`, `backend`, `docs`, `infrastructure`, `scripts` y `tests`.

- Móvil: Flutter y Dart.
- Backend: Python, Django y Django REST Framework.
- Base de datos: PostgreSQL.
- Panel web: HTML, CSS y JavaScript como base prevista; framework por decidir.
- Comunicación cliente-servidor: API REST sobre HTTPS.

## Multiinstitucionalidad

La primera estrategia a evaluar es una base de datos compartida con asociación explícita a institución y filtros de acceso aplicados obligatoriamente en backend. Se realizarán pruebas automáticas contra accesos cruzados. La estrategia deberá revisarse antes de datos reales y puede cambiar según requisitos contractuales o de seguridad.

## Consecuencias

Se mantiene una separación clara entre aplicaciones cliente y backend. Las tecnologías concretas, versiones, hosting y despliegue se decidirán y probarán al configurar el primer MVP.
