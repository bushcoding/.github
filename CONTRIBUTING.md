# Cómo contribuir

## Ramas

- `main` es lo que está en producción. No se trabaja directo sobre `main`.
- Creá una rama por cambio: `feature/<tema>`, `fix/<tema>` o `chore/<tema>`.
- Abrí un pull request y completá la plantilla.

## Commits

En inglés, modo imperativo, primera letra en mayúscula y sin punto final. Igual que los actuales:

```
Add multilingual API and email support
Enforce account-level plan limits
Hide unfilled AdSense slots
```

Un commit por cambio lógico. Evitá mensajes como `Update index.js`.

## Probar localmente

No hay CI: todo se verifica en tu máquina antes de abrir el PR.

- Corré los tests y el build del repo.
- Si cambia algo visible, revisalo en celular y en escritorio.

## Secretos y `.env`

- Nunca commitees `.env` ni claves, tokens o contraseñas.
- Cada variable nueva va en `.env.example` (sin el valor real) y en el README.
- Si cambia un dato o una clave de producción, prepará la migración en el mismo PR.

## Vulnerabilidades

No las reportes en issues. Seguí [SECURITY.md](SECURITY.md).
