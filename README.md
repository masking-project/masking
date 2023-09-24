# masking

(work in progress)

this is the command that wrapping/calling corresponding masking command via database tyoes.

```sh
mysqldump mydb | masking # -> calling masking project for MySQL
pg_dump pgdb | masking  # -> calling masking project for PostgreSQL
```

this project is an implementation of [Fractal Architecture](https://github.com/fractal-architecture)
