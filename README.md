# .github

Archivos de comunidad por defecto para todos los repositorios de la cuenta **bushcoding** en GitHub.

## Qué contiene

| Archivo | Para qué sirve |
| --- | --- |
| `pull_request_template.md` | Plantilla que aparece al abrir un pull request |
| `ISSUE_TEMPLATE/bug.yml` | Formulario para reportar errores |
| `ISSUE_TEMPLATE/feature.yml` | Formulario para proponer mejoras |
| `ISSUE_TEMPLATE/config.yml` | Desactiva issues en blanco y agrega el contacto por correo |
| `SECURITY.md` | Cómo reportar vulnerabilidades |
| `CONTRIBUTING.md` | Ramas, commits, pruebas locales y manejo de `.env` |

## Cómo los aplica GitHub

- Este repositorio tiene que llamarse exactamente `.github`, pertenecer a `bushcoding` y ser **público**.
- GitHub usa estos archivos en cada repositorio de `bushcoding` que **no tenga su propio archivo del mismo tipo** (en la raíz, en `.github/` o en `docs/`). Si un repo tiene el suyo, gana el del repo.
- Las plantillas de issues funcionan como un bloque: si un repo tiene su propia carpeta `.github/ISSUE_TEMPLATE/`, se ignoran todas las de acá para ese repo.
- No se copian archivos a los otros repos: GitHub los muestra desde acá. Tampoco aparecen al clonar.
- Solo aplica a repos de `bushcoding`, no a los de otras cuentas.

## Cómo cambiar algo

Editá el archivo acá y hacé push. El cambio se ve en todos los repos al instante.
