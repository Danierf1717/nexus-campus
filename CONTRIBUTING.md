# Guía de contribución

## Antes de contribuir

- Lee el `README.md` raíz y los documentos relevantes de `docs/`.
- No subas secretos, datos personales reales ni información institucional sin autorización.
- Mantén el aislamiento por institución en toda consulta, tarea, exportación y notificación.
- Añade pruebas para nuevas reglas de negocio y permisos.

## Ramas sugeridas

- `main`: versión estable del repositorio.
- `develop`: integración de trabajo cuando el equipo la necesite.
- `feature/nombre-corto`: funcionalidad nueva.
- `fix/nombre-corto`: corrección.
- `docs/nombre-corto`: documentación.

Para el inicio individual del proyecto, se puede trabajar directamente con ramas `feature/*` y fusionarlas a `main` mediante Pull Request.

## Commits sugeridos

Usa mensajes breves y descriptivos, por ejemplo:

- `docs: document initial project scope`
- `chore: add repository structure`
- `feat: add institution model`
- `test: add tenant isolation tests`
- `fix: validate request ownership`

## Pull Requests

Describe el cambio, el motivo, las pruebas realizadas y cualquier migración necesaria. No marques como implementado algo que solo esté documentado o planeado.
