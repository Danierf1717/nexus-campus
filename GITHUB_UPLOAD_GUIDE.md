# Guía para incorporar esta estructura a NEXUS CAMPUS

Este paquete contiene únicamente la estructura inicial y archivos de orientación. No contiene todavía una aplicación Flutter generada, un proyecto Django ejecutable ni un panel web implementado.

## Cómo incorporarlo sin perder el README actual

1. Descarga y extrae el ZIP en tu computadora.
2. Abre la carpeta local del repositorio `nexus-campus` en Visual Studio Code.
3. Copia el contenido extraído dentro de esa carpeta.
4. Cuando Windows pregunte, conserva el `README.md` que ya existe en la raíz. Este paquete no incluye un README raíz para evitar reemplazarlo.
5. Revisa los archivos nuevos y confirma que `.gitignore`, `.editorconfig`, `.env.example`, `apps/`, `backend/`, `docs/`, `infrastructure/`, `scripts/`, `tests/` y `.github/` aparezcan en la raíz.
6. Guarda los cambios con Git y súbelos a GitHub.

Mensaje de commit sugerido:
`chore: add initial monorepo structure`

## Qué está listo y qué no

- Listo: carpetas, documentación guía, `.gitignore`, `.editorconfig`, ejemplo de variables y una decisión arquitectónica inicial.
- Pendiente: generar Flutter, crear el proyecto Django, definir el framework final del panel web, instalar dependencias, configurar PostgreSQL y escribir funcionalidades.

No agregues contraseñas, tokens ni claves reales al repositorio. El archivo `.env` real debe mantenerse fuera de Git.
