# Backend — Django REST Framework

El backend será responsable de autenticación, autorización, lógica de negocio, validación multiinstitucional, API REST, auditoría y acceso a PostgreSQL.

## Estado

Esta es una carpeta de preparación. El proyecto Django todavía no ha sido generado. Antes de crear modelos y endpoints se validará el modelo de datos y el flujo MVP.

## Principios obligatorios

- Las aplicaciones cliente se comunican únicamente con la API.
- Cada petición protegida valida usuario, institución activa, rol, permiso y pertenencia del registro.
- Las consultas deben quedar filtradas por la institución correspondiente.
- Se usan datos ficticios durante desarrollo.
- Las claves se guardan en variables de entorno, nunca en Git.
