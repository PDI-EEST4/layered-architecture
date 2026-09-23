# Layered Architecture

## Requisitos

- PHP 8.1 o superior.
- Extensión PDO habilitada.
- MySQL o PostgreSQL según la configuración en el archivo `.env`.

## Migraciones

Colocá tus archivos `.sql` en `src/database/migrations/` y ejecuta:

```bash
composer migrate
```

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](./LICENSE).

---

Generado por la [plantilla](https://github.com/PDI-EEST4/slim-template-2026), a discreción de los integrantes del proyecto.
