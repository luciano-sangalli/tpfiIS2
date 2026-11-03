@"
# Política de seguridad

Este proyecto es un trabajo práctico académico (UADER-FCyT, Ingeniería de Software II).

## Reporte de vulnerabilidades

Escribir a nahuelzarax@gmail.com indicando qué se encontró, cómo reproducirlo y la versión utilizada. No incluir credenciales en el reporte.

## Medidas de seguridad aplicadas

- Las credenciales de AWS no forman parte del repositorio (``.gitignore``).
- ``bandit`` analiza el código en cada ejecución del CI.
- El repositorio es privado y se revisa ``git status`` antes de cada commit.
- Si una clave se publicara, se solicita su rotación a la cátedra.
"@ | Set-Content SECURITY.md -Encoding utf8